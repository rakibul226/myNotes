# myDevNote
-----------------------------_ _-------------------------------------

<pre>



-------------------------_fetch_using_React_Router_------------------


        {
            path:"/products",
            element:<Products></Products>,
            loader : ()=> fetch('https://dummyjson.com/products')
        },

        const Products = () => {
            const products= useLoaderData();
            console.log(products);
        }


-----------------------------_Get_pararms_-------------------------------------

        {
            path:'/products/:id',
            element:<ProductDetails></ProductDetails>,
            loader : ({params})=> fetch(`https://dummyjson.com/products/${params.id}`)

            // loader : ({params})=> console.log(params)
            // loader : (object)=> console.log(object.params.id)
        },
        const ProductDetails = () => {

        const productDetails = useLoaderData();

            return (
                <>
                </>
            )
        }























</pre>