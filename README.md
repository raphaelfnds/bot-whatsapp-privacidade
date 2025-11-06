# Política de Privacidade - Bot WhatsApp Extensão Cultural

**Última Atualização:** 06/11/2025

Bem-vindo ao Bot WhatsApp Extensão Cultural, desenvolvido por Raphael Fernandes como parte do Projeto de Extensão I da Engenharia de Software - Bacharelado (Ampli). Este bot promove a difusão cultural na Secretaria de Cultura de Ponta Grossa-PR, alinhado às ODS da ONU (4.7, 9.c, 11.4, 17.16). Esta Política de Privacidade explica como coletamos, usamos, protegemos e excluímos seus dados pessoais, em conformidade com as políticas da WhatsApp Business API da Meta e a Lei Geral de Proteção de Dados (LGPD) brasileira.

## 1. Informações Coletadas
Nosso bot coleta as seguintes informações mínimas quando você interage com ele via WhatsApp, apenas após seu consentimento explícito (opt-in):

- **Nome:** Fornecido voluntariamente para personalização das respostas.
- **Número de Telefone:** Obtido automaticamente como identificador da conversa no WhatsApp.
- **Aceitação de Termos:** Registro de sua concordância com esta política e os termos de uso (campo booleano "acceptedTerms").

Não coletamos dados sensíveis, como localização, conteúdo de mensagens além do necessário para o fluxo, ou informações de pagamento. Para a Etapa 2 (respostas dinâmicas via IA), consultas temporárias sobre agendas/editais são processadas em memória e não armazenadas.

## 2. Uso dos Dados
Os dados coletados são utilizados exclusivamente para:

- Fornecer respostas personalizadas sobre agendas e editais culturais (links fixos na Etapa 1; scraping e IA na Etapa 2, via Groq com modelo llama-3.1-8b-instant).
- Gerenciar o fluxo de conversa (estados em memória, com reset por inatividade ou "SAIR").
- Cumprir os objetivos educacionais do Projeto de Extensão, sem fins comerciais ou publicitários.
- Armazenar de forma segura no MongoDB Atlas (free tier) para registro de opt-in e personalização futura.

Os dados não são usados para treinamento de IA, profiling ou qualquer finalidade além da difusão cultural.

## 3. Compartilhamento de Dados
Não compartilhamos seus dados com terceiros, incluindo a Meta (exceto metadados necessários para a API WhatsApp), Groq ou outros serviços. Exceções: apenas se exigido por lei ou para cumprir obrigações regulatórias. Os dados são processados em servidores AWS (free tier) e MongoDB Atlas, com acesso restrito ao desenvolvedor.

## 4. Base Legal
A coleta e processamento baseiam-se no seu consentimento explícito (opt-in ao digitar "1" para confirmação), conforme Art. 7º, I da LGPD. O bot não inicia conversas proativas sem templates aprovados pela Meta. O projeto é educacional, sem remuneração ou vínculos empregatícios, alinhado à Resolução CNE/CES nº7/2018.

## 5. Seus Direitos
Você pode, a qualquer momento:
- Cancelar o opt-in e parar de receber mensagens enviando "SAIR" (exclui estados de conversa; dados no DB são mantidos por 30 dias para compliance, depois anonimizados).
- Solicitar acesso, correção ou exclusão de seus dados entrando em contato via raphael@softvibe.com.br (resposta em até 15 dias, conforme LGPD).
- Revogar consentimento sem afetar processamentos anteriores válidos.

## 6. Segurança dos Dados
Usamos medidas como criptografia em trânsito (HTTPS), IP liberado temporariamente (0.0.0.0/0 para IPs dinâmicos), e retenção mínima (dados excluídos automaticamente após inatividade prolongada). Em caso de violação, notificaremos os afetados conforme LGPD.

## 7. Contato
Para dúvidas ou exercícios de direitos, contate o desenvolvedor em raphael@softvibe.com.br. Consulte a documentação completa no GitHub: https://github.com/raphaelfnds/bot-whatsapp-privacidade.

**Nota:** Este é um projeto educacional sem fins lucrativos. Não utilizamos os dados para fins comerciais ou publicitários. Atualizações nesta política serão notificadas via bot ou GitHub.
