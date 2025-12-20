# trabalho-de-conclus-o-de-curso-Michael-Rafael-Andrade<br>
trabalho-de-conclus-o-de-curso-Michael-Rafael-Andrade created by GitHub Classroom<br>
  <br>
# Desenvolvimento de um Sistema ERP Gratuito para MPEs: Análise e Validação do Modelo de Sustentação por Publicidade e Doações.<br>
Software desenvolvido para o Trabalho de Conclusão de Curso (TCC) apresentado como exigência para obtenção do título de Especialista em Desenvolvimento Full Stack do Instituto Federal do Sudeste de Minas Gerais - Campus Manhuaçu.<br>
<br>
MICHAEL RAFAEL DE ANDRADE - 2026<br>
**Objetivo**: Viabilizar a digitalização e o controle de gestão para micro e pequenas empresas por meio de um software acessível, eliminando a barreira imposta pelos custos fixos e riscos financeiros inerentes à aquisição de sistemas profissionais pagos.<br>
<br>
Funcionalidades<br>
    • [x] Gestão de Estoque Completa.<br>
    • [x] Controle de Fluxo de Caixa.<br>
    • [x] Bloco de Notas para Lembretes Gerenciais.<br>
    • [x] Interface Totalmente Responsiva (Mobile-First).<br><br>

# Frontend: React.js, HTML5, CSS3, Bootstrap.<br>
# Backend: Node.js, Express.<br>
# Banco de Dados: MySQL.<br>
# ORM: Sequelize.<br>
# Arquitetura: MVC (Model-View-Controller).<br><br>
# Guia de Instalação<br>
<br>
<br>
## Guia de Instalação<br>
Clone repositório:<br><br>

git clone https://github.com/pos-FullStack/trabalho-de-conclus-o-de-curso-Michael-Rafael-Andrade<br><br>
    1. Instale as dependências:<br>
npm install<br>
<br>
    2. Configure o Banco de Dados:<br>
        ◦ Crie um banco de dados MySQL chamado erp_database.<br>
        ◦ Renomeie o arquivo .env.example para .env e insira suas credenciais de acesso.<br>
Execute as Migrations:<br>
npx sequelize-cli db:migrate <br>
    3. Inicie a aplicação:<br>
npm run dev<br>
