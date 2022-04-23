# RDGR-Product-Card

Este es un paquete de pruebas de despliegue en NPM.

## Ing. Reyes Diego Garrido Romero

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'rdgr-product-card';
```

```
<ProductCard
	product={product}
	initialValues={{
	    count: 4,
	    // maxCount: 10,
	}}
>
	{
        ({ increaseBy, reset, count, maxCount, isMaxCountReached }) => (
			<>
				<ProductImage />
				<ProductTitle />
				<ProductButtons />
			</>
		)
    }
</ProductCard>

```