# CI/CD para Hostinger sem SSH

O CI é o workflow [ci.yml](../.github/workflows/ci.yml): ele valida os arquivos estáticos e o JSON-LD em toda Pull Request e em cada `push` para a `master`.

O CD é executado pela integração nativa Git da Hostinger. Ela conecta o repositório ao hPanel por OAuth e publica automaticamente cada novo commit da branch configurada; não requer FTP, SSH, senha ou GitHub Secret.

## Configuração única do deploy

1. Abra **Hostinger → Websites → bikkofy.com.br → Manage site**.
2. Acesse **Advanced → Git**.
3. Escolha **Connect with GitHub** e autorize a aplicação Hostinger somente para `emersonfiwre/bikkoweb`.
4. Selecione o repositório `emersonfiwre/bikkoweb` e a branch `master`.
5. Defina o diretório raiz como `public_html` e conclua o primeiro deploy.
6. Na página Git, mantenha **Auto-deployment** ligado.

Depois disso, uma Pull Request valida o site no GitHub; quando ela for mesclada na `master`, a Hostinger detectará o push e publicará a versão automaticamente.

## Verificação

Na seção **Advanced → Git** da Hostinger, confira o histórico de deploys e o commit publicado. Se necessário, use **Redeploy** para disparar uma publicação manual da branch `master`.

> Esta configuração substitui o fluxo anterior por SFTP/SSH, pois o plano atual não oferece acesso SSH.
