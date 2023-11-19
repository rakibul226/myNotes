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

























</pre>