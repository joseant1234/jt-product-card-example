# JTU-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Jose

### Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons} from jtu-product-card';
```

```
<ProductCard
    product={product}
    initialValues={{
    count: 5,
    maxCount: 10,
    }}
>
    {
    ({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
        <>
        <ProductImage />
        <ProductTitle  />
        <ProductButtons  />
        </>
    )
    }
</ProductCard>
```
