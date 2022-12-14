---
title: Build commands live
date: 2022-10-28T05:54:01.918Z
description: "In Hugo, static files that don't need to be processed by the build
  commands live in the static/ directory. You'll install the Netlify CMS admin
  and config files there. Create a directory admin/ and within it, create two
  files index.html and config.yml. In the index.html, add the following
  content:"
image: img/about-direct-sourcing.jpg
---
In Hugo, static files that don't need to be processed by the build commands live in the `static/` directory. You'll install the Netlify CMS admin and config files there. Create a directory `admin/` and within it, create two files `index.html` and `config.yml`. In the `index.html`, add the following content In Hugo, static files that don't need to be processed by the build commands live in the `static/` directory. You'll install the Netlify CMS admin and config files there. Create a directory `admin/` and within it, create two files `index.html` and `config.yml`. In the `index.html`, add the following content In Hugo, static files that don't need to be processed by the build commands live in the `static/` directory. You'll install the Netlify CMS admin and config files there. Create a directory `admin/` and within it, create two files `index.html` and `config.yml`. In the `index.html`, add the following content:

<!--EndFragment-->



<!--StartFragment-->

### Deploying With Netlify

Now you can go ahead and deploy to Netlify. Go to your Netlify dashboard and click **[New site from Git](https://app.netlify.com/start)**. Select the repo you just created. Under **Basic build settings**, you can set the build command to `hugo` and the publish directory to `public`. Click **Deploy site** to get the process going.

### Authenticating with Netlify Identity

**Add the Netlify Identity Widget**

You've already added the Netlify Identity widget to our `admin/index.html`. The next thing to do is add the Netlify Identity widget to our site's index page. In `layouts/index.html`, we can add the following to the `<head>` tag on the page:

<!--StartFragment-->

**Le low-code et le no-code pourraient permettre d'acc??l??rer le d??veloppement et le d??ploiement des logiciels et de transformer les d??veloppeurs en facilitateurs. Une r??cente enqu??te men??e par OutSystems aupr??s des d??veloppeurs r??v??le qu'une majorit?? d'utilisateurs de Low-Code - dont la plupart utilisent ??galement des langages de codage traditionnels en plus du low-Code - se d??clarent "tr??s satisfaits" de la productivit?? de leur ??quipe (59 %), contre 41 % des d??veloppeurs traditionnels. Toutefois, bien que le d??veloppement no-code soit une option, il a des limites. Les plateformes no-code n'ont pas autant de flexibilit?? que le code et la s??curit?? peut ??tre un probl??me avec les plateformes no-code ou low-code, car on n'a pas le contr??le du code et il est potentiellement expos?? aux vuln??rabilit??s de la plateforme.**\
\
Seuls 48 % des d??veloppeurs sont convaincus qu'ils travailleront dans la m??me entreprise dans un an. L'essor de l'??conomie num??rique s'accompagne d'une demande quasi insatiable de d??veloppeurs de logiciels pour cr??er les applications et les plateformes dans le cloud qui alimenteront notre avenir. Les entreprises du monde entier ressentent la pression des d??veloppeurs, avec plus de 330 000 postes de d??veloppeurs ouverts aujourd'hui et une demande qui atteindra plus de quatre millions d'ici 2025, selon le cabinet d'??tudes IDC2.

<!--EndFragment-->