---
layout: page
title: Docentes
weight : 120
---

<style>
    .prof{
      margin: 0 0 40px;
      text-align: center;
    }

    .prof .cover-image{
      width: 100px;
      height: 100px;
      margin: 0 auto 10px;
      -webkit-border-radius: 100%;
              border-radius: 100%;
      overflow: hidden;
      background-color: #333030;
    }
    
    .prof{
      width: 10px;
      height: 100px;
      -webkit-border-radius: 50%;
              border-radius: 50%;
      -webkit-transition: -webkit-transform 0.35s;
      transition: -webkit-transform 0.35s;
      -o-transition: transform 0.35s;
      transition: transform 0.35s;
      transition: transform 0.35s, -webkit-transform 0.35s;
    }
    
    .prof:hover {
      -webkit-transform: scale3d(0.9, 0.9, 1);
              transform: scale3d(0.9, 0.9, 1);
    }

 .about {
   margin: 0 0 40px;
   text-align: center;
 }
 
 .about .cover-author-image {
   width: 100px;
   height: 100px;
   margin: 0 auto 10px;
   -webkit-border-radius: 100%;
           border-radius: 100%;
   overflow: hidden;
   background-color: #333030;
 }
 
 .about .proff {
   width: 100%;
   height: 100%;
   -webkit-border-radius: 50%;
           border-radius: 50%;
   -webkit-transition: -webkit-transform 0.35s;
   transition: -webkit-transform 0.35s;
   -o-transition: transform 0.35s;
   transition: transform 0.35s;
   transition: transform 0.35s, -webkit-transform 0.35s;
 }
 
 .about .proff:hover {
   -webkit-transform: scale3d(0.9, 0.9, 1);
           transform: scale3d(0.9, 0.9, 1);
 }
 
 .about .author-name {
   font-family: 'PT Serif', serif;
   margin: 0 0 10px;
   position: relative;
   padding-bottom: 15px;
   font-size: 16px;
   text-transform: uppercase;
   color: #333030;
}
 .about .author-name::after {
   content: "";
   position: absolute;
   left: 50%;
   -webkit-transform: translateX(-50%);
       -ms-transform: translateX(-50%);
           transform: translateX(-50%);
   bottom: 0;
   display: block;
   width: 7px;
   height: 7px;
   -webkit-border-radius: 100%;
           border-radius: 100%;
   background-color: #515151;
 }

</style>

{:class="about"}{:class="cover-author-image"}![Medina Sánchez, Tatiana]({{site.baseurl}}/assets/img/professors/Tatiana-Medina-Sanchez.jpg){:class="proff"}{:class="author-name"}Tatiana Medina Sánchez

|:--------------------------------------------------------:| --------------------------- |:----------------:|
| ![Leon Mogrovejo, Daphne]({{site.baseurl}}/assets/img/professors/Daphne-Leon-Mogrovejo.jpg){: .prof .cover-image}                   |  Leon Mogrovejo, Daphne      |  [website][web1] |
| ![Medina Sánchez, Tatiana]({{site.baseurl}}/assets/img/professors/Tatiana-Medina-Sanchez.jpg){:class="prof"}       | Medina Sánchez, Tatiana     |  [website][web2] |
| ![Pinto Rodriguez, Galvarino]({{site.baseurl}}/assets/img/professors/Galvarino-Pinto-Rodriguez.jpg){:class="prof"} | Pinto Rodriguez, Galvarino  |  [website][web3] |
| ![Simbort Zeballos, Enrique]({{site.baseurl}}/assets/img/professors/Enrique-Simbort-Zeballos.jpg){:class="prof"}   | Simbort Zeballos, Enrique   |  [website][web4] |
| ![Zeballos Velarde, Carlos]({{site.baseurl}}/assets/img/professors/Carlos-Zeballos-Velarde.jpg){:class="prof"}      | Zeballos Velarde, Carlos    |  [website][web5] |



[web1]: https://ucsp-civil.github.io/Daphne-Leon-Mogrovejo/
[web2]: https://ucsp-civil.github.io/Tatiana-Medina-Sanchez/
[web3]: https://ucsp-civil.github.io/Galvarino-Pinto-Rodriguez/
[web4]: https://ucsp-civil.github.io/Enrique-Simbort-Zeballos/
[web5]: https://ucsp-civil.github.io/Carlos-Zeballos-Velarde/
