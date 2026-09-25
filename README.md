### Hi, I'm Jacob

I work with data, and I've learned the numbers rarely lie. The trouble is what we choose to count, and what we'd rather not look at.

Most days that means turning a messy flow of information into something people can actually act on. I care less about pretty dashboards and more about whether the thing still works at 5 in the morning when nobody is watching.

**What I'm working on**

A media intelligence platform that reads the Danish news cycle so a communications team doesn't have to, running entirely on hardware I control.

- **Local LLM pipeline:** every article goes through an open-weight model (Qwen3, served with Ollama) that pulls out topics, quotes and who said them. No data leaves the building
- **Semantic search:** multilingual embeddings (bge-m3) stored in Postgres with pgvector, so you can search by meaning, not just keywords
- **Entity resolution:** a journalist and source registry that untangles messy bylines and ties every quote to the right person
- **Danish sentiment scoring** on coverage, built on a lexicon model rather than a black box
- **Real-time collaboration:** shared case documents synced between editors with CRDTs (Yjs) over Postgres realtime
- **Automated daily briefings** at 05:00, before anyone is awake to ask for one
- **Ops I actually trust:** self-hosted Supabase, encrypted off-site backups three times a day, and dead-man's-switch monitoring that notices within two minutes if anything goes quiet

**Things I believe**

- If you can't explain where a number came from, you don't have a number
- The most important column is usually the one nobody thought to add
- Boring infrastructure is a feature

**Tools I reach for**

Data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

Infrastructure

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

Most of my work lives in private repositories. Happy to talk about it though: [@DybdahlJacob](https://x.com/DybdahlJacob)
