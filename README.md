<p align="center">
  <img src="https://img.shields.io/badge/Radar_Tecnológico-GenAI-blueviolet?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Banner">
</p>

# 🛰 Radar de Tecnología Hands-On: Generative AI

## 🌟 Dream Stack Recomendado (Lunes 3 de febrero 2025)

### Infraestructura Base
- **Vector Hybrid RAG (español)**: PostgreSQL con [pgvector](https://github.com/pgvector/pgvector), [pg_trgm](https://www.postgresql.org/docs/current/pgtrgm.html)/[unaccent](https://www.postgresql.org/docs/current/unaccent.html) + [SQLAlchemy](https://www.sqlalchemy.org/) + [Alembic](https://alembic.sqlalchemy.org/)
- **Framework Agentes Productivos**: [DSPy](https://dspy.ai/)
- **Framework Agentes PoC**: [LangChain](https://www.langchain.com/)
- **Embeddings Español Técnico**: [JINA AI V3](https://jina.ai/news/jina-embeddings-v3-a-frontier-multilingual-embedding-model/)

### LLMs por Caso de Uso
- **Router Principal**: [Gemini 2.0 Flash](https://ai.google.dev/gemini-api/docs/models/gemini-v2)* 
- **Procesamiento de Datos**: [Gemini 2.0 Thinking](https://ai.google.dev/gemini-api/docs/thinking)*
- **Razonamiento Complejo**: [O1-pro](https://openai.com/index/introducing-chatgpt-pro/)
- **Búsqueda RAG**: [DeepSeek R1](https://github.com/deepseek-ai/DeepSeek-R1)
- **Coding**:
  - Tareas Complejas (+PRD/Reame/Docs/Webs): [O1-pro](https://openai.com/index/introducing-chatgpt-pro/)
  - Tareas Simples (+Docs/Webs): [DeepSeek R1](https://github.com/deepseek-ai/DeepSeek-R1)
  - Mucho Contexto (+800 lineas de código): [Gemini EXP 12-06](https://ai.google.dev/gemini-api/docs/models/gemini-v2)
- **IDE Recomendado**: [Cursor](https://www.cursor.com/)

> *Nota: Los modelos Gemini requieren implementación multipool + validación por estar en fase experimental.

## 🤖 Principales Modelos de IA

### OpenAI
- **Modelo O1-Pro** - Modelo empresarial para tareas complejas. Destaca en razonamiento pero requiere optimización especializada de prompts, alejándose del patrón tradicional. Aún no soporta navegación ni ejecución de código.
  [Documentación](https://openai.com/index/introducing-chatgpt-pro/)
- **Modelo O3-Mini-High** - Versión optimizada para desarrollo rápido, con excelente desempeño en Python. Presenta limitaciones con lenguajes imperativos y de 4ta generación como SQL y scripting.
  [Documentación](https://openai.com/index/openai-o3-mini/)

### Claude
- **Sonnet 3.5** - El modelo más balanceado para desarrollo de código. Sobresale por su baja tasa de alucinaciones y alta precisión.
  [Anuncio oficial](https://www.anthropic.com/news/claude-3-5-sonnet)

### Gemini (Google)
- **Gemini 2.0** - Nueva generación de modelos de Google con capacidades mejoradas.
  [Guía técnica](https://deepmind.google/technologies/gemini/flash/)
- **Gemini 2.0 Flash** - Optimizado para velocidad de respuesta. En fase experimental, presenta desafíos en programación y tareas complejas. Requiere validación exhaustiva (15-20% de revisiones). Destaca en procesamiento multimodal (texto, pdfs, imagen, video) y necesita integrarse con arquitecturas de validación de contenido (Prometheus) para flujos agénticos, tiene muchas fallas en el response schema.
  [Documentación API](https://ai.google.dev/gemini-api/docs/models/gemini-v2)
- **Gemini 2.0 Thinking** - Especializado en razonamiento complejo. Reduce significativamente la necesidad de ingeniería de prompts y sobresale en el procesamiento de PDFs complejos.
  [Guía de implementación](https://ai.google.dev/gemini-api/docs/thinking)

### DeepSeek
- **DeepSeek-R1** - Modelo open-source que supera a los modelos de Google en calidad de respuesta. Si bien es más lento en procesamiento, su disponibilidad a través de múltiples proveedores en OpenRouter lo hace muy accesible.
  [GitHub oficial](https://github.com/deepseek-ai/DeepSeek-R1)  
  [Acceso via OpenRouter](https://openrouter.ai/deepseek/deepseek-r1:free)

## 🔧 Tecnologías Auxiliares

### Frameworks de Agentes (bajo nivel)
- **DSPy** - El más estable para producción. Minimalista en abstracción aunque con dependencias significativas como Tenacity.
  [Documentación](https://dspy.ai/)
- **LangChain** - Ideal para prototipado rápido. Sus múltiples capas de abstracción y necesidad de formateo para flujos agénticos lo hacen menos recomendable para producción.
  [Sitio oficial](https://www.langchain.com/)
- **LlamaIndex** - Solución enterprise en desarrollo, aún requiere maduración.
  [Plataforma](https://www.llamaindex.ai/)

### Embeddings
- **JINA AI V3**
  - Embeddings multilingües de última generación
  - [Detalles técnicos](https://jina.ai/news/jina-embeddings-v3-a-frontier-multilingual-embedding-model/)

- **Google Embeddings API**
  - Solución cloud escalable
  - [Documentación oficial](https://ai.google.dev/api/embeddings)

- **OpenAI Embeddings**
  - Integración nativa con modelos OpenAI
  - [Guía de uso](https://platform.openai.com/docs/guides/embeddings)

### 🖥 Herramientas de Desarrollo
- **Cursor**: IDE con IA integrada ([Sitio oficial](https://www.cursor.com/))
- **Windsurf**: Desarrollo asistido por IA ([Plataforma](https://codeium.com/windsurf))

### 🧠 Sistemas RAG
- **Google Vertex AT**: RAG empresarial ([Guía cloud](https://cloud.google.com/vertex-ai/docs/rag-overview))
- **ChromaDB**: Base vectorial open-source ([Documentación](https://www.chromadb.dev/))
- **PostgreSQL pgvector**: Extensión vectorial ([Repositorio](https://github.com/pgvector/pgvector))

---

## 👨‍💻 Autor

**Karim Touma**  
STEM Polymata

📧 [karim@touma.io](mailto:karim@touma.io)  
🌐 [karim.touma.io](https://karim.touma.io)  
💼 [LinkedIn](https://www.linkedin.com/in/katouma/)  
🐦 [Twitter](https://x.com/karim_op)

---

<p align="center">
✨ Radar activo - Actualizado febrero 2025 ✨<br>
Proyecto educativo para seguimiento y democratización de tecnologías de IA Generativa
</p>

