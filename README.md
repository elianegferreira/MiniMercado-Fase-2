Funcionalidades – MiniMercado Online
fase 2

🛠️ 1.Ajustes fase 1

-troca de imagem para o carrossel

-Incluisão mais um artigo por categoria de produto

📄2. Estrutura Geral

-O site é composto por 4 páginas principais:

-Início (index.html)

-Produtos (produtos.html)

-Serviços (servicos.html)

-Cadastro de Cliente (cadastro.html)

Todas elas seguem o mesmo padrão visual com:

-Cabeçalho com logo e menu de navegação

-Carrossel de imagens com Bootstrap

-Rodapé com informações organizadas em colunas

-Cores e tipografia padronizadas com tons de verde

🖼️ 3. Página Inicial (index.html)

-Mensagem de boas-vindas centralizada

-Carrossel automático com 4 imagens representando o mercado

-Container com 2 colunas temáticas (Alimentação e Casa), contendo:

-Imagem representativa

-Texto descritivo

-Layout responsivo com bordas

-Container com 1 coluna temática (Comodidade), contendo:

-Imagem representativa

-Texto descritivo


🛒 4. Página de Produtos (produtos.html)

Lista de produtos dividida em 3 categorias:
Frutas e Verduras, Alimentos não Perecíveis e Higiene e Limpeza

Cada produto exibido em card com:

-Imagem

-Nome, preço, unidade

-Campo de quantidade

-Botão "Adicionar ao Carrinho"

Funcionalidades via JavaScript:

-Soma dos valores selecionados em tempo real

-Botão muda para “Adicionado!” e volta após 3 segundos

-Total acumulado exibido no final da página

-Lista de compras dinâmica com opção de remover produto

🛎️ 5. Página de Serviços (servicos.html)

Seção em dois cards:

-Retirada no Local (serviço gratuito, com agendamento)

-Tele-Entrega (agendamento disponível)

-Destaque com cores, bordas e ícones para cada serviço

Formulário de agendamento com:

-Seleção de tipo de serviço

-Campo de data (calendário)

-Horários disponíveis (dropdown)

-Botão para simular envio

🧾 6. Página de Cadastro (cadastro.html)

Formulário completo com:

-Nome, e-mail, CPF, telefone

-Gênero, endereço dividido em campos (logradouro, número, CEP, etc.)

-Campo para observações

Campos com:

-required (obrigatórios)

-placeholder

-pattern para validar CPF e CEP

-autofocus

-Mensagem de agradecimento após o envio (via redirecionamento)

♿ 7. Acessibilidade

-Imagens possuem o atributo alt com audiodescrição adequada para leitores de tela

-Botões e links com contraste e legibilidade

-Uso de tags semânticas (<section>, <nav>, <footer>)
