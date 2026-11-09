# 🔥 Path of Flames

Landing page oficial de **Path of Flames**, um RPG de ação offline ambientado nas terras de Zahra. Apresente o universo do jogo e ofereça downloads para Android e Windows em uma experiência responsiva.

![Status](https://img.shields.io/badge/status-em_desenvolvimento-green.svg)
![Versão](https://img.shields.io/badge/vers%C3%A3o-0.13.4-orange.svg)
![Site estático](https://img.shields.io/badge/site-est%C3%A1tico-blue.svg)

---

## 📌 Índice

- [Visão Geral](#-visão-geral)
- [Tecnologias](#-tecnologias)
- [Como Executar](#-como-executar)
- [Como Contribuir](#-como-contribuir)
- [Licença](#-licença)

---

## 💡 Visão Geral

Este repositório contém a página de divulgação e distribuição de **Path of Flames**. O jogo é uma aventura solo e offline com 12 capítulos, exploração e uma história sobre as Sete Chamas Sagradas.

- ✨ **Apresentação do jogo:** história, cenários e informações sobre as atualizações.
- 📱 **Design responsivo:** experiência adaptada para computadores e celulares.
- ⬇️ **Downloads diretos:** versões atuais para Android e Windows.
- ♿ **Acessibilidade:** suporte a movimento reduzido e navegação por teclado.

### Downloads

- [Android — versão 0.13.4 (APK)](downloads/Path%20of%20Flames.apk)
- [Windows — versão 0.13.4 (instalador)](downloads/Path-of-Flames-Setup-0.13.4.exe)

> **Android:** o APK 0.13.2 distribuído anteriormente usa outra assinatura e pode exigir desinstalação antes de instalar esta versão. Isso pode apagar dados locais.

---

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript
- Imagens e downloads servidos como arquivos estáticos

Não é necessário React, Node.js, Docker ou um processo de build para executar a página.

---

## 🚀 Como Executar

### Pré-requisitos

- [Git](https://git-scm.com/)
- [Python 3](https://www.python.org/) para iniciar um servidor local (opcional)

### Passo a passo

```bash
# Clone este repositório
git clone https://github.com/elielreinan/pof-landing.git

# Acesse a pasta do projeto
cd pof-landing

# Inicie um servidor local
python -m http.server 8000
```

Abra <http://localhost:8000> no navegador. Também é possível abrir `index.html` diretamente, mas um servidor local representa melhor a hospedagem.

---

## 🤝 Como Contribuir

1. Abra uma issue para relatar um problema ou propor uma melhoria.
2. Crie uma branch para sua alteração.
3. Faça as alterações e teste a página em computador e celular.
4. Envie um pull request com uma descrição clara do que mudou.

Ao atualizar versões, mantenha os nomes dos arquivos em `downloads/` sincronizados com os links e as informações de versão em `index.html`.

---

## 📄 Licença

Este repositório não contém atualmente um arquivo de licença. Até que uma licença seja definida, não presuma que o código, as imagens ou os materiais do jogo podem ser reutilizados ou redistribuídos.
