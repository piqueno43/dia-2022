# Modificações que podem ser passadas via html.

## Logo
### Opções tse ou tre-xx
```html
<img src="https://www.tse.jus.br/++theme++justica_eleitoral/imagens/logos/tse.png" alt="" />
<img src="https://www.tse.jus.br/++theme++justica_eleitoral/imagens/logos/tre-al.png" alt="" />
```

## Cor do card
### Opções `green`, `purple`, `red`, `orange`, `yellow`.

```html
  <!-- Escolhe a cor do card as opções são: green, red, purple -->
  <section class="card card-green">...</section>    
```
## Card com ícone
### Opção `has-icon`.
```html
  <!-- Indica se existe ou não o ícone -->
  <main class="card-content has-icon">...</main>
  <main class="card-content">...</main>  
```
## Ícones
### Opções `candidaturas`, `denuncias`, `imprensa`, `je`, `justificativa`, `mesario`, `resultados` e `titulo`.

```html  
  <span class="card-icon titulo"></span>
```
## Estrutura do card

```html
<section class="card card-green">
  <header class="card-header">
    <h3 class="card-title">Título</h3>
  </header>
  <main class="card-content has-icon">
    <span class="card-icon titulo"></span>
    <ul class="card-list">
      <li class="card-list-item">
        <a href="#" data-drawer-target="drawer-bottom-local-votacao" data-drawer-show="drawer-bottom-local-votacao" data-drawer-placement="bottom" aria-controls="drawer-bottom-local-votacao" type="button">Local de votação</a>
      </li>
      <li class="card-list-item"><a href="https://www.tse.jus.br/eleitor/titulo-e-local-de-votacao/copy_of_consulta-por-nome">Situação eleitoral</a></li>
      <li class="card-list-item"><a href="https://www.justicaeleitoral.jus.br/titulo-eleitoral/">e-Título</a></li>
    </ul>
  </main>
</section>
```
## Grid do formulário
### Opções `md:grid-cols-1`, `md:grid-cols-2`, `md:grid-cols-3`, `md:grid-cols-4` e `md:grid-cols-5`.
```html
  <div class="form-control md:grid-cols-3">
```