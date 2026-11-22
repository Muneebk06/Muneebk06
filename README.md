# Muneeb Ur Rehman

**AI undergraduate · BIIT, Rawalpindi · CGPA 3.96/4.00**  
**[LinkedIn ↗](https://www.linkedin.com/in/muneeb-ur-rehman-ai/)**　·　[Email me](mailto:Mk6821860@gmail.com)

![Pixel-art illustration of a student at a computer vision workstation in Rawalpindi](assets/vision-lab.gif)

## ▸ Featured build　/　[BIIT Vision OS](https://github.com/Muneebk06/biit-vision-os)

My first attendance model had a problem on day one of a new class. Every time a student joined, I had to retrain the classifier. In BIIT Vision OS, enrolling a student means saving a **128-dimensional face embedding**. The model can stay exactly as it is.

**What happens at the camera?** MobileNetV2 produces an embedding for each detected face. The app compares it with enrolled students, labels weak matches *Unknown*, and takes a vote across ten frames before recording attendance. A 30-second cooldown keeps the same student from being marked twice in quick succession.

`MobileNetV2`　`Triplet loss`　`OpenCV`　`Firebase`

**[Explore BIIT Vision OS →](https://github.com/Muneebk06/biit-vision-os)**

## ▸ Cartridge shelf

[![YouTube Research Agent — transcript explorer](assets/youtube-cartridge.svg)](https://github.com/Muneebk06/Youtube-ai-research-Ai-agent)

Follow-up questions kept fetching the same video transcript. I added a cache so the agent could spend its token budget on the next question.  
`LangChain` · `Groq` · `FastAPI` · `Streamlit`

[![Resilience Nexus — Earth observation](assets/nexus-cartridge.svg)](https://github.com/Muneebk06/Resilience-Nexus)

A team competition project for exploring forest cover and flood predictions across 17 districts. The forest model reached **64.73% mIoU on 187 held-out patches**. Abdullah contributed the trained flood model.  
`Landsat` · `TensorFlow` · `LightGBM`

[![Retail Inventory — desktop systems](assets/retail-cartridge.svg)](https://github.com/Muneebk06/CSharp-SQL-Retail-Inventory)

A shop records a sale once. SQL Server handles the stock change, and the desktop app reads the updated inventory for its reports.  
`C#` · `WinForms` · `SQL Server`
