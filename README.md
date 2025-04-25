# PPSD Práctica 3. Protección de datos II

- **Criptografía moderna**
    - [x] Cryptool RSA
    - [x] OpenSSL
    - [x] Cryptool D&H (falta generar las claves con Cryptool)
- **Certificados digitales**
    - [x] Certificados HTTPS (faltan las capturas de openssl)
    - [ ] Certificado digital
- **PGP y S/MIME**
    - [ ] Generar Claves
    - [ ] Thunderbird
    - [ ] Outlook
    - [ ] GPG
    - [ ] S/MIME
    - [ ] Firma KeepassXC
- **Privacidad**
    - [ ] Cookies
    - [ ] Política de cookies -> me lo pido (alicia)
    - [ ] Cookies en Firefox -> me lo pido (alicia)
    - [ ] ProtonVPN
    - [ ] VPN UDC
    - [x] TOR

# Pequeña guía de compilación

Al intentar compilar el pdf con `pdflatex main.tex` seguramente encontremos un par de errores/warnings.
Para evitar esto y compilarlo exitosamente debemos primero compilar con el comando `pdflatex -shell-escape main.tex`, a continuación compilar la bibliografía con `biblatex main` (sin el `.tex` del nombre) y finalmente compilar el *main* de nuevo con `pdflatex -shell-escape main.tex`. Quizás haga falta compilar dos veces con `pdflatex`, como es común en LaTeX local :P
