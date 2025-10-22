<img align="center" alt="banner" src="imgs/banner.png">

# Proyecto devbydap

Este es el proyecto completo de HUGO que genera el blog [dev.davidalvarezp.com](https://dev.davidalvarezp.com)

## ¿Qué es devbydap?

devbydap es una iniciativa de [davidalvarezp](davidalvarezp.com)

## Objetivos:
- Distribucion de software
- Implementación de nuevas tecnologías

## ¿Cómo contribuir?

1. Contactar a [davidalvarezp](https://davidalvarezp.com)
2.Solicitar permiso para contribución



6. And voila! You're ready to go. The codespace has been configured with the latest version of Hugo extended, just run `hugo server` in the terminal and see your new site in action.

7. Check `config` folder for the configuration files. You can edit them to suit your needs. Make sure to update the `baseurl` property in `config/_default/config.toml` to your site's URL.

8. Open Settings -> Pages. Change the build branch from `master` to `gh-pages`.
![Build](https://github.com/namanh11611/hugo-theme-stack-starter/assets/16586200/12c763cd-bead-4923-b610-8788f388fcb5)

9. Once you're done editing the site, just commit it and push it. GitHub action will deploy the site automatically to GitHub page asociated with the repository.
![GitHub action](https://user-images.githubusercontent.com/5889006/156916881-90b8bb9b-1925-4e60-9d7a-8026cda729bf.png)

---

In case you don't want to use GitHub codespace, you can also run this template in your local machine. **You need to install Git, Go and Hugo extended locally.**

## Update theme manually

Run:

```bash
hugo mod get -u github.com/TuNombre/hugo-theme-stack/v3
hugo mod tidy
```


![image](https://github.com/zhi-yi-huang/hugo-theme-stack-starter/assets/83860323/777c1109-dfc8-4893-9db7-1305ec027cf5)


Make sure also to specify Hugo version in the environment variable `HUGO_VERSION` (Use the latest version of Hugo extended):

![Environment variable](https://user-images.githubusercontent.com/5889006/156917212-afb7c70d-ab85-480f-8288-b15781a462c0.png)
</details>
