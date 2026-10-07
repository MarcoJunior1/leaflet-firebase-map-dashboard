# 🗺️ Mapa de Líderes — DF

Dashboard interativo para **mapear lideranças por região do Distrito Federal**, com visualização em mapa, cadastro de líderes, totais por cidade e **exportação de relatório em PDF**.

## ✨ Funcionalidades

- 🗺️ **Mapa interativo** (Leaflet + OpenStreetMap) centrado no DF
- 📍 Painel de **Regiões** e **totais por cidade** (ex.: Ceilândia, Samambaia, Taguatinga, Brazlândia…)
- 👥 Aba **Líderes**: adicionar, editar e excluir líderes
- 🔧 Aba **Admin**: ajuste de setores/dados com mapa de edição
- ☁️ **Sincronização em tempo real** com **Firebase Firestore** (indicador de status de conexão)
- 📄 **Exportar PDF** do relatório

## 🛠️ Tecnologias

HTML · CSS · JavaScript · Leaflet · Firebase (Firestore + Hosting)

## 🗂️ Estrutura

```
├── index.html       # aplicação inteira
├── 404.html         # página de erro
├── firebase.json    # configuração do Firebase Hosting
└── .firebaserc      # projeto Firebase (dashboard-mapa-lideres-silvana)
```

## 🚀 Como executar / publicar

```bash
# local: abra index.html no navegador (ou use um servidor estático)
npm install -g firebase-tools
firebase login
firebase deploy --only hosting
```

Para usar seu próprio banco, crie um projeto no Firebase, ative o Firestore e substitua o `firebaseConfig` no `index.html`. **Configure as regras de segurança do Firestore** para restringir quem pode gravar.

## 📝 Autor

[Marco Júnior](https://github.com/MarcoJunior1)

