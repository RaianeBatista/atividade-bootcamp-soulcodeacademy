# Guia de Cores Bootstrap - NexTech

## 📋 Como Usar as Cores Personalizadas

Este arquivo contém todas as cores do Bootstrap 5 e algumas personalizações extras para sua aplicação.

## 🎨 Cores Principais Disponíveis

### Cores Básicas do Bootstrap:

-   `bg-primary` (azul)
-   `bg-secondary` (cinza)
-   `bg-success` (verde)
-   `bg-danger` (vermelho)
-   `bg-warning` (amarelo/laranja)
-   `bg-info` (azul claro)
-   `bg-light` (cinza claro)
-   `bg-dark` (preto)

### Cores Extras Adicionadas:

-   `bg-blue` (azul puro)
-   `bg-indigo` (índigo)
-   `bg-purple` (roxo)
-   `bg-pink` (rosa)
-   `bg-red` (vermelho puro)
-   `bg-orange` (laranja)
-   `bg-yellow` (amarelo)
-   `bg-green` (verde puro)
-   `bg-teal` (verde-azulado)
-   `bg-cyan` (ciano)
-   `bg-gray` (cinza)
-   `bg-gray-dark` (cinza escuro)

## 📝 Exemplos de Uso

### 1. Background (Fundo):

```html
<div class="bg-orange">Fundo laranja</div>
<nav class="navbar bg-purple">Navbar roxa</nav>
<button class="btn bg-teal text-white">Botão verde-azulado</button>
```

### 2. Texto:

```html
<p class="text-orange">Texto laranja</p>
<h1 class="text-purple">Título roxo</h1>
<span class="text-teal">Texto verde-azulado</span>
```

### 3. Bordas:

```html
<div class="border border-orange">Borda laranja</div>
<card class="border border-purple">Card com borda roxa</card>
```

### 4. Botões Personalizados:

```html
<button class="btn btn-orange">Botão Laranja</button>
<button class="btn btn-purple">Botão Roxo</button>
<button class="btn btn-teal">Botão Verde-azulado</button>
<button class="btn btn-blue">Botão Azul</button>
```

### 5. Tons Claros e Escuros:

```html
<div class="bg-blue-light">Azul claro</div>
<div class="bg-blue-dark">Azul escuro</div>
<div class="bg-green-light">Verde claro</div>
<div class="bg-green-dark">Verde escuro</div>
```

### 6. Gradientes:

```html
<div class="bg-gradient-blue">Gradiente azul</div>
<div class="bg-gradient-sunset">Gradiente pôr do sol</div>
<div class="bg-gradient-ocean">Gradiente oceano</div>
<div class="bg-gradient-forest">Gradiente floresta</div>
```

### 7. Transparências:

```html
<div class="bg-blue-transparent">Fundo azul transparente</div>
<div class="bg-orange-transparent">Fundo laranja transparente</div>
```

### 8. Sombras Coloridas:

```html
<div class="shadow-blue">Sombra azul</div>
<div class="shadow-orange">Sombra laranja</div>
<div class="shadow-purple">Sombra roxa</div>
```

## 🚀 Exemplos Práticos para sua Navbar

```html
<!-- Navbar laranja -->
<nav class="navbar navbar-expand-lg bg-orange">
    <!-- Navbar com gradiente -->
    <nav class="navbar navbar-expand-lg bg-gradient-sunset">
        <!-- Navbar roxa -->
        <nav class="navbar navbar-expand-lg bg-purple">
            <!-- Navbar verde-azulada -->
            <nav class="navbar navbar-expand-lg bg-teal"></nav>
        </nav>
    </nav>
</nav>
```

## 💡 Dicas de Combinações

### Combinações que funcionam bem:

-   `bg-orange` + `text-white`
-   `bg-purple` + `text-light`
-   `bg-teal` + `text-dark`
-   `bg-blue` + `text-white`
-   `bg-gradient-sunset` + `text-white`

### Para cards e seções:

```html
<div class="card bg-blue-light border-blue">
    <div class="card-body text-blue-dark">
        <h5 class="card-title text-blue">Título do Card</h5>
        <p class="card-text">Conteúdo do card...</p>
    </div>
</div>
```

## 🔧 Personalização

Você pode modificar as cores no arquivo `css/custom-colors.css` alterando as variáveis CSS:

```css
:root {
    --bs-orange: #fd7e14; /* Altere aqui para sua cor preferida */
    --bs-purple: #6f42c1; /* Altere aqui para sua cor preferida */
}
```

## 📁 Estrutura de Arquivos

```
projeto-landing/
├── index.html (arquivo principal)
├── css/
│   └── custom-colors.css (suas cores personalizadas)
├── bootstrap-5.3.7-dist/
│   ├── css/
│   │   └── bootstrap.min.css
│   └── js/
│       └── bootstrap.bundle.min.js
└── README-cores.md (este arquivo)
```

Agora você tem acesso a todas as cores do Bootstrap e pode usar qualquer uma delas em sua aplicação! 🎨
