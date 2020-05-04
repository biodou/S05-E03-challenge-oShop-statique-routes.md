# Routes

## Sprint 1

| URL | HTTP Method | Controller | Method | Title | Content | Comment |
|--|--|--|--|--|--|--|
| `/` | `GET` | `MainController` | `home` | Dans les shoe | 5 categories | - |
| `/public-url/legal-mentions` | `GET`| `MainController` | `legalMentions` | mentions légales  | legal mentions | no dynamic |
| `/public-url/catalog/category/[id]` | `GET`  | `CatalogController` | `category` | catégorie #12 | display of the category #12 | `[12]` |
| `/public-url/catalog/type/[id]` | `GET` | `CatalogController` | `type` | Type | type of article | `[40]` |
| `/public-url/catalog/brand/[id]` | `GET` | `CatalogController` | `brand` | Marque | Marque  | `[2]` |
| `/public-url/catalog/product/[id]` | `GET` | `CatalogController` | `product` | Article | The product | `[4]` |
| `/public-url/with-sub-folder/[and-dynamic-part]` | `GET` ou `POST` | `ControllerName` | `methodName` | Titre de la page | Description of page's content | Explain here the dynamics parts of your URL (`[]`) |
