# Deploy no Vercel

## Para publicar sua aplicação Vue no Vercel, siga estes passos:

### 1. **Prepare o repositório GitHub**
   - Certifique-se de que o projeto está commitado no Git
   ```bash
   git add .
   git commit -m "Preparar para deploy no Vercel"
   git push
   ```

### 2. **Acesse o Vercel**
   - Vá para [https://vercel.com](https://vercel.com)
   - Faça login com sua conta (você pode usar GitHub, GitLab, Bitbucket ou Google)

### 3. **Novo Projeto**
   - Clique em "New Project" ou "Add New..."
   - Selecione seu repositório do GitHub (alura-tracker-vue)

### 4. **Configuração Automática**
   - O Vercel detectará automaticamente que é um projeto Vue CLI
   - As configurações padrão devem funcionar:
     - **Framework Preset**: Vue.js
     - **Build Command**: `npm run build`
     - **Output Directory**: `dist`
     - **Install Command**: `npm install`

### 5. **Deploy**
   - Clique em "Deploy"
   - Aguarde o processo de build e deploy (geralmente 2-5 minutos)

### 6. **Próximos Deploys**
   - A cada push no branch `main` (ou padrão), o Vercel faz deploy automático
   - Preview automático para PRs

## ✅ Seu projeto está configurado para Vercel!

- `vercel.json` foi criado com as configurações corretas
- Build de produção testado e funcionando
- Pronto para ir ao ar!

## Dúvidas?
Para mais informações: [https://vercel.com/docs](https://vercel.com/docs)
