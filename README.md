# metacognition-framework-web · v1.52.0 (tier PÚBLICO — chat, sem filesystem)

> **GERADO do repo main** (`tools/web_export.py`). **Não editar à mão** (sentido único; ADR-054/057/058).

Encarnação **chat** do Framework Metacognitivo para ambientes **sem filesystem** (Claude.ai, Gemini, ChatGPT). Autocontido, grátis (CC BY 4.0).

## Como usar (3 passos)
1. Abra um chat com instruções de projeto: **Claude.ai** (Projects → Instruções), **Gemini** (Gem → Instruções) ou **ChatGPT** (Custom GPT → Instructions).
2. **Cole o conteúdo de `prompt-web-publico.md`** como a instrução de sistema/projeto.
3. Converse — o método (classificar confiança, file-first, anti-alucinação, validação, decisões registradas) já governa as respostas. **Sem instalar nada.**

## O que esperar (e o que NÃO)
- ✅ Método metacognitivo: confiança (CONFIRMADO/INFERIDO/NÃO SEI), validação, anti-fabricação.
- ❌ **Sem gates de runtime** (hooks/effect-gate/sync): no chat não há filesystem nem execução — o método vale por LEITURA, não por mecanismo. Efeito irreversível **sempre pede sua confirmação** (doutrina anti-JARVIS: nunca finge mecanismo que o chat não executa).

## Quer mais?
- **Squad por papéis no chat** → tier PREMIUM (pago): repo `metacognition-framework-web-premium`.
- **Framework COMPLETO (clona e roda, com hooks/tools/gates reais)** → repo `metacognition-framework` — **esta aqui é só a versão chat, não o full.**
