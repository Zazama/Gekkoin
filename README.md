# Gekkoin
## A small and clean CSS Framework

### Media Queries
```
----------------------------------------------    /* Standard  s-* */
@media only screen and (max-width: 1200px) { }    /* DESKTOP   d-* */
@media only screen and (max-width: 992px)  { }    /* Tablet    t-* */
@media only screen and (max-width: 768px)  { }    /* Phablet   p-* */
@media only screen and (max-width: 480px)  { }    /* MOBILE    m-* */
```

### Grid system

#### Usage

```
<!-- Main wrapper -->
<div class="container">
    <!-- All columns should be inside a row container -->
    <div class="row">
        <!-- column ranging from one to twelve -->
        <!-- 25% Standard - 33% on Desktop - 50% on Tablet - 100% on Mobile -->
        <div class="column s-3 d-4 t-6 m-12"></div>
    </div>
    <div class="row">
        <!-- 25% as Standard, Desktop and Tablet - 33% on Phablet - 100% on Mobile -->
        <div class="column s-4 p-3 m-12"></div>
    </div>
</div>

<!-- For 100% width container -->
<div class="container fluid">
    <div class="row">
        <!-- Gap between elements with offset -->
        <div class="column s-8"></div>
        <div class="column s-3 offset-s-1"></div>
    </div>
</div>
```

#### Container sizes
| Mobile | Phablet | Tablet | Desktop | Standard |
| :----: | :-----: | :----: | :-----: | :------: |
| 90%    | 90%     | 750px  | 970px   | 1170px   |
