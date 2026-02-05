# 🍽️ Yahnova Brands - Sistema de Gestão Gastronômica

Sistema web completo para gestão de custos, precificação e composição de pratos.

## 📦 Arquivos

- `index.html` - Aplicativo web principal
- `yahnova_dados.json` - Base de dados (produtos, insumos, configurações)
- `README.md` - Este arquivo

## 🚀 Como usar no GitHub Pages

### 1. Criar repositório
1. Acesse [github.com](https://github.com)
2. Clique em "New repository"
3. Nome: `yahnova-app` (ou outro nome)
4. Marque "Public"
5. Clique em "Create repository"

### 2. Upload dos arquivos
1. Clique em "uploading an existing file"
2. Arraste os 3 arquivos:
   - `index.html`
   - `yahnova_dados.json`
   - `README.md`
3. Clique em "Commit changes"

### 3. Ativar GitHub Pages
1. Vá em "Settings" (configurações)
2. No menu lateral, clique em "Pages"
3. Em "Source", selecione "main" branch
4. Clique em "Save"
5. Aguarde 1-2 minutos
6. Seu site estará em: `https://SEU-USUARIO.github.io/yahnova-app/`

## ✏️ Como editar os dados

### Editar preços de insumos/produtos:

1. No GitHub, clique em `yahnova_dados.json`
2. Clique no ícone de lápis (Edit)
3. Edite os valores que quiser
4. Clique em "Commit changes"
5. Aguarde 1 minuto e recarregue o site

### Exemplo de edição:

```json
{
  "nome": "Arroz Branco",
  "custo_por_porcao": 0.56  ← MUDE AQUI
}
```

### Adicionar novo produto:

```json
{
  "nome": "Nome do Produto",
  "categoria": "GRÃOS",
  "sku": "PM#123",
  "peso_kg": 0.13,
  "custo_por_porcao": 5.00,
  "custo_por_kg": 38.46
}
```

## 🔧 Configurações do sistema

No arquivo `yahnova_dados.json`, seção `config`:

```json
"config": {
  "taxa_ifood": 0.26,        ← Taxa do iFood (26%)
  "custo_embalagem": 2.50,   ← Custo da embalagem
  "simples_nacional": {
    "faixa1": {
      "limite": 180000,
      "aliquota": 0.06       ← 6% para primeira faixa
    }
  }
}
```

## 📱 Funcionalidades

### 📊 Dashboard
- Visão geral de custos e produtos
- KPIs em tempo real
- Produtos por categoria

### 🔍 Busca Inteligente
- Busca instantânea
- Clique para ver ficha técnica completa
- Status visual de custos

### 💰 Calculadora Real
- Taxa iFood / WhatsApp / Presencial
- Custo de embalagens
- Simples Nacional
- Lucro líquido real

### 📈 Analytics
- Todos os produtos por categoria
- Ordenação por custo
- Insights para composições econômicas

### 🎯 Montador de Pratos
- Ajuste de porções (+/-)
- Cálculo automático de peso e custo
- **Geração de PDF** com ficha técnica

## 💡 Dicas

- **Backup**: Antes de editar, baixe uma cópia do JSON
- **Validação**: Use [jsonlint.com](https://jsonlint.com) para verificar erros
- **Atualização**: Mudanças aparecem em ~1 minuto após commit

## 🆘 Suporte

Se tiver problemas:
1. Verifique se os 3 arquivos estão no repositório
2. Confirme que GitHub Pages está ativado
3. Aguarde 2-3 minutos após qualquer mudança
4. Limpe o cache do navegador (Ctrl+Shift+R)

---

**Desenvolvido para Yahnova Brands** 🍽️
