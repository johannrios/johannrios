# Johann Ríos | Quant Developer & Software Engineer

Desarrollador enfocado en la construcción de infraestructura soberana para el análisis cuantitativo y la ejecución automatizada en mercados financieros. Mi enfoque radica en la latencia cero, la integridad de los datos de series de tiempo y la validación matemática de estrategias.

##  Core Stack & Architecture

Mi infraestructura de desarrollo y producción se basa en arquitecturas modularizadas, priorizando el control absoluto del entorno y el procesamiento determinista:

*   **Data Ingestion & Storage:** Implementación de pipelines asíncronos mediante WebSockets para captura de ticks en tiempo real (L1/L2 Order Book data), persistidos en bases de datos orientadas a series de tiempo (**TimescaleDB / QuestDB**).
*   **Execution Logic & Modeling:** Desarrollo de motores de riesgo y backtesting usando **Python**, y **C**.
*   **Agentic Engineering & AI:** Orquestación de modelos de lenguaje locales (Open Weights / DeepSeek) para análisis de sentimiento, validación de código y agentes de investigación.
*   **Infrastructure Ops:** Despliegues *containerizados* (**Docker**), gestión de entornos locales en **Linux (Ubuntu)**, automatización de terminal (TMUX) y flujos CI/CD rigurosos.

##  Filosofía Cuantitativa

En el diseño de sistemas de trading, desecho la heurística visual en favor de la robustez estadística. Todo modelo debe someterse a la maximización del rendimiento ajustado al riesgo, evaluando constantemente el **Ratio de Sharpe**:

$$S_p = \frac{E[R_p - R_f]}{\sigma_p}$$

Donde asumo que la ventaja matemática (*Edge*) solo es explotable cuando el sistema está diseñado para operar fuera del ruido blanco ($\epsilon_t$) del mercado, validado mediante *Walk-Forward Optimization* y *Combinatorial Purged Cross-Validation*.

##  Proyectos Actuales

*   **Algorithmic Trading Engine:** Motor de ejecución concurrente que desacopla la ingestión de datos, la generación de señales algorítmicas y el control de riesgo dinámico.
*   **Harness Engineering Platform:** Entorno de pruebas automatizado para validar la resistencia de estrategias operativas ante *Drawdowns* históricos antes de tocar producción.

---

