# openai2z-mcps
Data-sources useful for OpenAI to Z challenge wrapped into MCP servers and available for all.

## What is this?

It is interesting to use challeges like https://scrollprize.org or open ended like [this](https://openai.com/openai-to-z-challenge/) as a test bed or eval for general-purpose scientific discovery agent. Assuming future ASI will look smth like a small reasoning model with a trillion token context length, this repo provides the "trillon token" context length part of that agent and aims to be a center source of data for all participants of [openai-to-z-challenge](https://openai.com/openai-to-z-challenge/). Slighly against the bitter lesson, but in respect for efficiency this this challenge, it would be good to package each dataset with tools that are specifically useful to work with the dataset (like a lidar dataset can come with comunity selected best CV model fitting pipelines, or object type db can come with elastic search, and etc.). To make it stantardised and simple ot use, we guess thats where MCP comes in handly thus we provide every possible dataset as an MCP server.

The inspiration is to leave creative ideas for prompts / scafolding / choice of models for solving openai.com/openai-to-z-challenge for competing participants, but make data available for all, and in the most efficient manner.

## Contribute a dataset
1. [Building MCP with LLMs](https://modelcontextprotocol.io/tutorials/building-mcp-with-llms)

## References
1. [Starter PDF](https://cdn.openai.com/pdf/a9455c3b-c6e1-49cf-a5cc-c40ed07c0b9f/starter-pack-openai-to-z-challenge.pdf)
2. [OpenAI blog-post](https://openai.com/openai-to-z-challenge/)
3. [Discord invite](https://discord.gg/TEfk6NbgxF)
4. Fisher, C., Bogdanov, P., Mooney, P., Keating, N., & Demkin, M. (2025). *OpenAI to Z Challenge*. Kaggle. [https://kaggle.com/competitions/openai-to-z-challenge](https://kaggle.com/competitions/openai-to-z-challenge)

## TODOs

### 🏗️ Satellite imagery and map sources:
- [ ] **Google Earth Engine (GEE):** one‑click access to Sentinel‑1/‑2, NICFI, GEDI, SRTM, and Landsat.
- [ ] **European Space Agency:** a surplus of incredible open-source data collected over the last decades.
- [ ] **NASA:** The NASA catalogue is open to use and home to 25,000+ data sets.
- [ ] **OpenTopography LiDAR:** High-res canopy-penetrating elevation (1–10 m).
- [ ] **Sentinel‑2 optical imagery:** 10 m, 13-band scenes (good for vegetation scars).
- [ ] **AWS CLI:** covers swaths of western Amazon.

### 🏗️ Archaeological point data:
- [ ] **The Archeo Blog:** shares sampled data already drawn from the Amazonian region.

### 🏗️ Academic references with links:
- [ ] Clasby, Ryan, and Jason Nesbitt (2021) — *The Archaeology of the Upper Amazon*  
  https://books.google.com/books?hl=en&lr=&id=B4DSEAAAQBAJ&oi=fnd&pg=PP1&dq=amazon+lidar+archaeology&ots=oK0FItet27&sig=oFAGRog0cFkX9MooeDiaoRvVWzs#v=onepage&q=amazon%20lidar%20archaeology&f=false
- [ ] Cohen, Klassen & Evans (2020) — *Ethics in Archaeological Lidar*  
  https://journal.caa-international.org/articles/10.5334/jcaa.48
- [ ] de Souza et al. (2018) — *Pre-Columbian earth-builders along the southern rim of the Amazon*  
  https://www.nature.com/articles/s41467-018-03510-7
- [ ] Gomes, Denise (2025) — *Urban Archaeology in the Lower Amazon*  
  https://www.tandfonline.com/doi/full/10.1080/00934690.2025.2466877
- [ ] Iriarte et al. (2020) — *Geometry by Design*  
  https://journal.caa-international.org/articles/10.5334/jcaa.45
- [ ] Khan, Aragão & Iriarte (2017) — *UAV–lidar system to map Amazonian rainforest*  
  https://www.tandfonline.com/doi/abs/10.1080/01431161.2017.1295486
- [ ] Prümers et al. (2022) — *Lidar reveals pre-Hispanic low-density urbanism in Bolivian Amazon*  
  https://www.nature.com/articles/s41586-022-04780-4
- [ ] Peripato et al. (2023) — *10,000+ hidden pre-Columbian earthworks*  
  https://www.science.org/doi/10.1126/science.ade2541
- [ ] Wagner et al. (2022) — *Fast computation of terrain anomalies for geoglyph detection*  
  https://www.tandfonline.com/doi/full/10.1080/2150704X.2022.2109942
- [ ] Walker et al. (2023) — *Predicting ancient Amazonian site distribution with ML*  
  https://peerj.com/articles/15137/
- [ ] Stenborg et al. (2018) — *Contours of the Past*  
  https://www.tandfonline.com/doi/full/10.1080/00934690.2017.1417198

### ✅ Online Research Repositories:
- [ ] **Internet Archive:** library of text, audio, and video materials.
- [ ] **Library of Congress expedition books:** public-domain sources with detailed river‑mile diaries and Indigenous village locations.

