# O Meu Método — Guia de Instalação

## O que é isto?
O teu sistema pessoal de vida. Funciona 100% no browser — sem base de dados, sem servidor, sem custos.

Os dados (tracker, notas, desafios feitos) ficam guardados automaticamente no teu dispositivo com localStorage.

---

## Como colocar online em 3 passos

### Passo 1 — Cria uma conta GitHub
1. Vai a **github.com**
2. Clica "Sign up"
3. Cria a conta (é grátis)

### Passo 2 — Cria o repositório e faz upload
1. No GitHub, clica no **+** (canto superior direito) → "New repository"
2. Nome: `meu-metodo`
3. Escolhe **Public** (necessário para Vercel grátis)
4. Clica "Create repository"
5. Clica **"uploading an existing file"**
6. Arrasta os 2 ficheiros: `index.html` e `vercel.json`
7. Clica "Commit changes"

### Passo 3 — Liga ao Vercel
1. Vai a **vercel.com**
2. Clica "Sign Up" → escolhe "Continue with GitHub"
3. Clica **"Add New Project"**
4. Seleciona o repositório `meu-metodo`
5. Clica **"Deploy"**
6. Em 30 segundos tens um link tipo: `meu-metodo.vercel.app`

**Pronto. O teu sistema está online.**

---

## Notas importantes

### Os dados ficam no dispositivo
- O tracker e as notas ficam guardados no browser onde abres
- Se abrires noutro browser ou dispositivo, começa do zero
- Isto é normal — é privado e só teu

### Para ter os dados em todos os dispositivos
No futuro, se quiseres sincronizar entre telemóvel e computador, podes usar o **Supabase** (grátis) como base de dados. Mas não precisas agora — começa simples.

### Para atualizar o sistema
1. Editas o `index.html` no GitHub diretamente (clicas no ficheiro → lápis)
2. O Vercel atualiza automaticamente em segundos

---

## Estrutura do projeto
```
meu-metodo/
├── index.html    ← o teu sistema completo
└── vercel.json   ← configuração do Vercel
```

---

Criado com 💛 — para a mulher que está a tornar-se.
