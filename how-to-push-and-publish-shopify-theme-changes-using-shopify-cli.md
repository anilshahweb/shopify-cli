How to Push and Publish Shopify Theme Changes Using Shopify CLI?
Shopify theme ke changes ko store me upload aur publish karne ke liye:
Sabse pahle saare changes complete kar lenge.
Uske baad existing themes ki list dekhne ke liye shopify theme list command ka use karenge.
Uske baad jis theme me changes upload karne hain, uski Theme ID note kar lenge.
Uske baad selected existing theme me changes upload karne ke liye shopify theme push --theme theme-id command ka use karenge.
Example:
shopify theme push --theme 153850151139
Uske baad agar selected theme pehle se published (live) hai, to browser me website ko refresh kar denge aur latest changes show hone lagenge.
Lekin agar selected theme unpublished hai, to Shopify Admin me Online Store → Themes par jaakar us theme ko preview kar lenge.
Uske baad agar sab kuch sahi lage, to Publish button par click kar denge.
Uske baad latest changes website par show hone lagenge.
