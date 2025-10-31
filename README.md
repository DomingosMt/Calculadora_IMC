<img width="1854" height="830" alt="image" src="https://github.com/user-attachments/assets/f11032f4-eecf-4591-942f-ef17c9ecee04" />


# Calculadora IMC

Aplicação web simples e responsiva para calcular o IMC (Índice de Massa Corporal) a partir do peso (kg) e altura (m), exibindo o valor calculado e a classificação correspondente.

> Aviso: esta ferramenta tem propósito educativo. Para avaliação clínica, procure um profissional de saúde.

## 🌐 Demonstração (GitHub Pages)
Acesse a versão publicada: https://domingosmt.github.io/Calculadora_IMC

## ✨ Funcionalidades
- Entrada de peso em kg e altura em metros
- Cálculo instantâneo do IMC no envio do formulário
- Exibição do valor do IMC com duas casas decimais
- Classificação do IMC conforme faixas comuns de referência
- Destaque visual quando o resultado está na faixa ideal
- Layout responsivo (mobile-first com media queries)

## 🧠 Como o IMC é calculado
Fórmula:

IMC = peso (kg) / altura * altura (m)

Faixas utilizadas na aplicação:
- Abaixo de 18,5: Abaixo do peso
- 18,5 a 25: Peso ideal
- 25 a 30: Sobrepeso
- 30 a 35: Obesidade moderada
- 35 a 40: Obesidade severa
- Acima de 40: Obesidade mórbida

Os intervalos acima são os mesmos implementados em `assets/js/script.js`.

## 📁 Estrutura do projeto
```
Calculadora IMC/
  ├─ assets/
  │  ├─ css/
  │  │  └─ style.css         # Estilos e responsividade
  │  ├─ images/
  │  │  └─ illustration.svg  # Ilustração da página
  │  └─ js/
  │     └─ script.js         # Lógica de cálculo e UI
  └─ index.html               # Estrutura principal da aplicação
```

## 🧩 Tecnologias e bibliotecas
- HTML5 semanticamente simples
- CSS3 com Google Fonts (Poppins) e responsividade via media queries
- JavaScript (DOM API) para cálculo e manipulação de classes/elementos
- Font Awesome (CDN) para ícones

## 🚀 Executando localmente
1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
   - Dica no Windows: clique duas vezes em `index.html`.
   - Alternativa: sirva com um servidor estático (ex.: VS Code Live Server).

Não há dependências ou build: é um projeto 100% estático.

## 🧪 Uso
1. Informe o peso em quilogramas no campo "Peso em Kg".
2. Informe a altura em metros (ex.: 1.75) no campo "Altura em metros".
3. Clique em "Calcular".
4. Veja o IMC calculado e a descrição da faixa correspondente.

Observações:
- O campo de altura aceita casas decimais (`step="any"`).
- O valor exibido do IMC usa vírgula como separador decimal.

## 🌐 Publicando no GitHub Pages
1. Faça commit e push do projeto para um repositório no GitHub.
2. No GitHub, vá em Settings → Pages.
3. Em "Source", escolha a branch (geralmente `main`) e a pasta `/root` (ou `/docs` se você mover os arquivos para lá).
4. Salve. A URL publicada deste projeto: https://domingosmt.github.io/Calculadora_IMC

Como o projeto é estático, não precisa de configurações adicionais.

## ♿ Acessibilidade e UX
- Contraste adequado entre texto e fundo nos resultados
- Tamanhos de fonte legíveis e estrutura simples
- Ícones de apoio visual via Font Awesome
- Sugestão futura: adicionar `aria-live` na área de resultado e rótulos mais descritivos para leitura de tela

## 🛠️ Personalização
- Cores e tipografia: edite `assets/css/style.css` (variáveis/cores nos seletores principais).
- Lógica de faixas e mensagens: ajuste os intervalos e textos em `assets/js/script.js`.
- Ícones: a fonte de ícones está em CDN; substitua classes `fa-...` conforme necessário.

## ⚠️ Limitações
- Não trata entradas inválidas (ex.: zero, negativos) além do `required` HTML.
- Classificações de IMC não substituem avaliação clínica individual.

## 🤝 Contribuição
1. Faça um fork do repositório
2. Crie um branch para sua feature/fix: `git checkout -b minha-feature`
3. Commit: `git commit -m "feat: descreva sua mudança"`
4. Push: `git push origin minha-feature`
5. Abra um Pull Request

## 📜 Licença
Este projeto está licenciado sob a licença MIT. Sinta-se livre para usar e modificar.

## 📎 Créditos
- Ícones: Font Awesome (CDN)
- Fonte: Google Fonts (Poppins)
- Ilustração: `assets/images/illustration.svg`

---
Se este projeto foi útil, considere dar uma ⭐ no GitHub!
