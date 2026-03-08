# Rubeus - Teste Técnico

Segue minhas observações sobre os dois sites propostos no teste técnico:

1.  **Certificação:** [https://qualidade.apprbs.com.br/certificacao](https://qualidade.apprbs.com.br/certificacao)
2.  **Site:** [https://qualidade.apprbs.com.br/site](https://qualidade.apprbs.com.br/site)

Resolvi criar esse repositório mesmo não realizando testes automatizados, pois o formulário de envio no site atingiu o limite máximo de caracteres. Fico à disposição para um bate-papo.

---

## 🔗 Link 1 - Certificação
[Acesse aqui](https://qualidade.apprbs.com.br/certificacao)

### **Item 01 - Botão "Saiba mais" inacessível**
* **Tipo:** Correção
* **Classificação:** Utilidade
* **Prioridade:** Média
* **Descrição:** Na página inicial (1º bloco - Faculdade Exemplo), não foi possível clicar no botão "saiba mais" para o usuário obter mais informações.

### **Item 02 - Texto dos parágrafos e títulos desalinhados**
* **Tipo:** Melhoria
* **Classificação:** Desejabilidade
* **Prioridade:** Baixa
* **Descrição:** Na página inicial (2º bloco - Lorem Ipsum), os parágrafos ao lado do formulário estão formatados incorretamente. Os títulos estão com padding excessivo e desalinhados.

### **Item 03 - Imagem com "aspect ratio" incorreto**
* **Tipo:** Melhoria
* **Classificação:** Desejabilidade
* **Prioridade:** Baixa
* **Descrição:** No 2º bloco, a imagem do "consultor" está com as propriedades de proporção incorretas, causando distorção visual.

### **Item 04 - Formulário sem funcionamento esperado**
* **Tipo:** Correção
* **Classificação:** Utilidade
* **Prioridade:** Alta
* **Descrição:** Mesmo com dados válidos, o formulário não é enviado. A mensagem de erro ("É necessário informar a base legal") é genérica e prejudica a experiência.

### **Item 05 - Textos e colunas desalinhadas**
* **Tipo:** Melhoria
* **Classificação:** Desejabilidade
* **Prioridade:** Baixa
* **Descrição:** No 3º bloco, os textos estão descentralizados e com margens incorretas. Revisar: `margin-top`, `line-height` e `justify`.

### **Item 06 - Containers com larguras diferentes**
* **Tipo:** Melhoria
* **Classificação:** Desejabilidade
* **Prioridade:** Baixa
* **Descrição:** No 5º bloco, os containers possuem larguras inconsistentes e uma das imagens está "achatada".

### **Item 07 - Imagens cortadas nos cards**
* **Tipo:** Melhoria
* **Classificação:** Desejabilidade
* **Prioridade:** Baixa
* **Descrição:** No bloco "Outros cursos", as imagens dos containers 2 e 3 estão cortadas (possível problema no `object-fit`).

### **Item 08 - Erros de ortografia nos botões**
* **Tipo:** Melhoria
* **Classificação:** Desejabilidade
* **Prioridade:** Baixa
* **Descrição:** No bloco "Outros cursos", os containers 1 e 3 possuem erros ortográficos no botão "saiba mais".

### **Item 09 - Botão "Saiba mais" não clicável**
* **Tipo:** Correção
* **Classificação:** Usabilidade
* **Prioridade:** Média
* **Descrição:** No bloco "Outros cursos", os botões não possuem o atributo `href` nem redirecionamento funcional.

### **Item 10 - Redirecionamento incorreto (Certificação)**
* **Tipo:** Correção
* **Classificação:** Usabilidade
* **Prioridade:** Alta
* **Descrição:** O botão "Quero me certificar" redireciona incorretamente para o Google.

### **Item 11 - Ícone do Youtube leva ao Tiktok**
* **Tipo:** Correção
* **Classificação:** Usabilidade
* **Prioridade:** Alta
* **Descrição:** No Footer, o ícone do Youtube está configurado com o link do Tiktok da Rubeus.

---

## 🔗 Link 2 - Site
[Acesse aqui](https://qualidade.apprbs.com.br/site)

### **Item 01 - Botão Atendimento vs WhatsApp**
* **Tipo:** Correção
* **Classificação:** Usabilidade
* **Prioridade:** Alta
* **Descrição:** No header, o botão de Atendimento redireciona para o WhatsApp, duplicando a função de outro botão existente.

### **Item 02 - Link do WhatsApp incompleto**
* **Tipo:** Correção
* **Classificação:** Usabilidade
* **Prioridade:** Média
* **Descrição:** O botão abre o aplicativo do WhatsApp, mas não inicia a conversa com um número específico (falta o parâmetro de número).

### **Item 03 - Alinhamento de textos nos cards**
* **Tipo:** Melhoria
* **Classificação:** Desejabilidade
* **Prioridade:** Baixa
* **Descrição:**
