# Desafio-de-Projeto-AWS---A-Import-ncia-da-Seguran-a
Três serviços da AWS que eu recomendaria para aumentar a segurança do sistema de uma farmácia fictícia:

1. **AWS Identity and Access Management (IAM)**: O IAM permite gerenciar o acesso a serviços e recursos da AWS de forma segura. Com o IAM, você pode criar e gerenciar usuários e grupos da AWS e usar permissões para permitir e negar o acesso deles aos recursos da AWS. Isso é essencial para garantir que apenas pessoas autorizadas tenham acesso aos dados sensíveis.

2. **Amazon Inspector**: É um serviço de segurança automatizado que ajuda a melhorar a segurança e conformidade de aplicativos implantados na AWS. O Amazon Inspector avalia automaticamente os aplicativos em busca de vulnerabilidades ou desvios das melhores práticas. Após realizar uma avaliação, o Amazon Inspector produz um relatório detalhado com as descobertas prioritárias.

3. **AWS Shield**: É um serviço gerenciado que fornece proteção contra ataques de negação de serviço distribuído (DDoS) para aplicações na AWS. O AWS Shield fornece detecção de DDoS sempre ativa e mitigação automática que minimiza o tempo de inatividade e latência do aplicativo.

Para implementar essas ferramentas, você precisará seguir as etapas abaixo:

1. **AWS IAM**:
   - Crie usuários IAM para cada pessoa que precise de acesso ao seu console da AWS.
   - Crie grupos IAM para definir permissões que você pode atribuir a vários usuários, simplificando o gerenciamento de permissões.
   - Ative o MFA (autenticação multifator) para uma camada adicional de segurança durante o login.

2. **Amazon Inspector**:
   - Defina o escopo da avaliação e execute a avaliação.
   - Analise os resultados da avaliação no console do Amazon Inspector.

3. **AWS Shield**:
   - Escolha o tipo de proteção que melhor se adapta às suas necessidades (AWS Shield Standard ou AWS Shield Advanced).
   - Configure a proteção AWS Shield para seus recursos usando o AWS Management Console, AWS CLI ou SDKs da AWS.

Lembre-se, a segurança na nuvem é uma responsabilidade compartilhada entre a AWS e o cliente. A AWS é responsável pela segurança "da" nuvem, enquanto o cliente é responsável pela segurança "na" nuvem.

https://academiapme-my.sharepoint.com/:t:/g/personal/renato_dio_me/ESfphVPFtDhOsIfOWyy-7eEBroH_JfQMCrDxBF7zhuGoWQ?e=JfpgWM
