<h1 align="center">ECOMMERCE QUANTUM</h1>

<p align="center">	
   <a href="https://www.linkedin.com/in/rafael-goulartb/">
      <img alt="Rafael Goulart" src="https://img.shields.io/badge/-RafaelGoulartB-blue?style=flat&logo=Linkedin&logoColor=white" />
   </a>
  <a href="https://github.com/RafaelGoulartB/Next.js-Ecommerce#readme">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/RafaelGoulartB/Next.js-Ecommerce/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/RafaelGoulartB/Ecommerce-Quantum/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" target="_blank" />
  </a>
  <img alt="GitHub Pull Requests" src="https://img.shields.io/github/issues-pr/RafaelGoulartB/Next.js-Ecommerce" />
  <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/RafaelGoulartB/Next.js-Ecommerce" />
  <img alt="" src="https://img.shields.io/github/repo-size/RafaelGoulartB/Next.js-Ecommerce" />
</p>

> This project was made to show a full ecommerce plataform with front-end build with Next.Js hosting by Vercel. And using the API in next.Js with GraphQL to make the backend.

<p align="center">
    <a href="README.md">English</a>
    ·
    <a href="README-pt.md">Portuguese</a>
 </p>

<div align="center">
  <sub>The ecommerce project. Built with ❤︎ by
    <a href="https://github.com/RafaelGoulartB">Rafael Goulart</a> and
    <a href="https://github.com/RafaelGoulartB/Next.js-Ecommerce/graphs/contributors">
      contributors
    </a>
  </sub>
</div>

# :pushpin: Table of Contents

* [Demo Website](#eyes-demo-website)
* [Technologies](#computer-technologies)
* [Features](#rocket-features)
* [How to run](#construction_worker-how-to-run)
* [Found a bug? Missing a specific feature?](#bug-issues)
* [Contributing](#tada-contributing)
* [License](#closed_book-license)

<h2 align="left"> 📥 Layout available at: </h2>
<p align="center">
    <a title="Acess Figma Web" href="https://www.figma.com/file/fDLkOXAz4k3ILWb8PoDivJZF/E-Commerce-Quantum?node-id=0%3A1">
        <img alt="Direct Download" src="https://img.shields.io/badge/Acess Figma Web-black?style=flat-square&logo=figma&logoColor=red" width="200px" />
    </a>
</p>

### Screenshots
<div align="center">
  <img src="https://github.com/RafaelGoulartB/Ecommerce-Quantum/blob/master/Ecommerce.jpg" width="580">
</div>


# :eyes: Demo Website
The demo website can be missing some features, clone and run the project to a full experience. <br>
👉  demo: https://quantum-ecommerce.now.sh/

# :computer: Technologies
This project was made using the follow technologies:

* [Next.js](https://nextjs.org/) - To SSR and routes control     
* [GraphQL](https://graphql.org/) - To query language     
* [Apollo](https://www.apollographql.com/) - To graphql server and client       
* [Knex](https://knexjs.org/) - ORM   
* [Vercel](https://vercel.com/) - To deploy website     

# :rocket: Features

- Authentication with Cookies Sessions.
- Reset Password using email
- List Products
- Filter products by Category
- Sort list of products
- Live search
- Add products to Wishlist
- Add products to Cart
- Checkout with Paypal and MercadoPago
- Payment with Paypal and MercadoPago
- Review Products
- Contact us Form

# :construction_worker: How to run
### Install Dependencies
```bash
yarn install
```
### Set up database
```bash
# Create DB using migrations
yarn knex:migrate

# Run seeds to populate database
yarn knex:seed 
```
### Run Aplication
```bash 
yarn dev 
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
<br>
<br>
Open [http://localhost:3000/api/graphql](http://localhost:3000/api/graphql) with your browser to run queries or to see docs of API.


# :bug: Issues

Feel free to **file a new issue** with a respective title and description on the the [NextJS Ecommerce](https://github.com/RafaelGoulartB/Next.js-Ecommerce/issues) repository. If you already found a solution to your problem, **i would love to review your pull request**!

# :tada: Contributing

Check out the [contributing](./CONTRIBUTING.md) page to see the best places to file issues, start discussions and begin contributing.

# :closed_book: License

Released in 2020.
This project is under the [MIT license](./LICENSE).

Made with love by [RafaelGoulartB](https://github.com/RafaelGoulartB) 🚀
