# Relatório Técnico: Verificação de Clonagem de Cartões

## 1. Estrutura Semântica (HTML5)
- **Header**: Contém o título da página.
- **Main**: Agrupa o conteúdo principal (formulário e alerta).
- **Form**: Para coleta de dados do cartão, com campos obrigatórios e validação básica.
- **Footer**: Informações de direitos autorais.
- **Divs e Classes**: Usadas para agrupar elementos e aplicar estilos.

## 2. Estilização (CSS3)
- **Cores Temáticas**:
  - Azul (`#0066cc`) para elementos primários.
  - Amarelo (`#ffcc00`) para botões e destaques.
  - Vermelho (`#dc3545`) para alertas de erro.
- **Layout**:
  - Flexbox para centralização vertical e horizontal.
  - Container com largura máxima de 600px para melhor leitura.
- **Responsividade**:
  - Media queries para ajustar padding e fontes em telas menores (430px).
  - Layout flexível com unidades relativas (`rem`, `%`).

## 3. Funcionalidades (JavaScript)
- **Validação Client-Side**: Usa `pattern` para validar números de cartão e CVV.
- **Simulação de Processamento**: Delay de 1,5 segundos para mostrar o resultado.
- **Timestamp Aleatório**: Gera um número aleatório de milissegundos para o "tempo de clonagem".

## 4. Separação Estrutura/Estilização
### Vantagens:
1. **Manutenção**: Alterar o CSS não afeta o HTML.
2. **Reusabilidade**: Classes CSS podem ser reaproveitadas.
3. **Acessibilidade**: HTML semântico é melhor interpretado por leitores de tela.
4. **Performance**: Estilos independentes permitem otimizações.

### Reflexão:
A separação entre estrutura (HTML) e estilização (CSS) é essencial para:
- Desenvolver sites escaláveis.
- Facilitar a colaboração em equipe.
- Garantir compatibilidade com diferentes dispositivos.

## 5. Responsividade
- **Desktop (1920x1080)**:
  - Layout centralizado com largura máxima de 600px.
  - Fonte maior para melhor legibilidade.
- **Mobile (430x932)**:
  - Padding reduzido para aproveitar o espaço.
  - Fontes ajustadas para telas pequenas.

## 6. Referências
- [MDN Web Docs](https://developer.mozilla.org/pt-BR/)
- [W3Schools](https://www.w3schools.com/)
- [Google Fonts](https://fonts.google.com/)