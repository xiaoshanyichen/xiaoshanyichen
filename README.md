# Hi, I'm Yichen, you can call me Simon 👋

### I build intelligent systems that have to work beyond the demo.

I'm a computer science graduate student at Georgia Tech with a software engineering background from McGill. I enjoy the seams between **machine learning, systems, and real-world products** - the places where a model needs good data, honest evaluation, reliable infrastructure, and a thoughtful interface before it becomes useful.

My favorite projects are end to end: I like taking an idea from a rough experiment to something measurable, debuggable, and usable by an actual person.

## What I'm exploring

- **Generative models you can evaluate.** I built conditional and unconditional diffusion pipelines for multi-channel geological facies data, then designed the probability-map, distributional, Sliced-Wasserstein, and embedding-based evaluations used to compare model iterations.
- **Accessible AI that can move with you.** For [**CyberGlass**](https://github.com/yutingli1123/CyberGlass), my team is building low-cost smart glasses that turn live scenes into spoken descriptions. I worked across an ESP32-S3, a [Flutter companion app](https://github.com/yutingli1123/CyberGlassApp), multimodal AI, and a custom 8-channel BLE protocol that reached 2.5 fps without relying on Wi-Fi.
- **Software that explains its failures.** My work in test automation made me care about observability as much as correctness - from reusable page models and resilient waits to per-action screenshots and network logs.

## Selected builds

| Project | The interesting part | Built with |
| --- | --- | --- |
| [CyberGlass firmware](https://github.com/yutingli1123/CyberGlass) + [companion app](https://github.com/yutingli1123/CyberGlassApp) *(team capstone)* | An ESP32-S3 camera streams images over 8 parallel BLE channels to a Flutter app with proactive narration, object finding, bidirectional audio, and haptic feedback | C++, PlatformIO, Flutter, BLE, Gemini Live API |
| **Generative facies modeling** *(research)* | Conditional diffusion over 4-channel spatial data, with an evaluation suite built to reveal more than a single score | PyTorch, Hugging Face Diffusers |
| [Chinese OCR correction corpus](https://github.com/xiaoshanyichen/Automated-Generation-of-Chinese-Text-Correction-Corpora) | Turns disagreement between PDF text extraction and OCR into paired correction data; includes a T5-style correction pipeline | Python, PaddleOCR, Hugging Face |
| [Simulated operating system shell](https://github.com/xiaoshanyichen/simple-operating-system) | Scheduling, multithreading, demand paging, LRU eviction, and a small filesystem-like command environment | C |
| [Cross-genre semantic role labeling](https://github.com/xiaoshanyichen/NLP-SRL-Cross-Genre-Evaluating-Semantic-Role-Labeling-with-Pretrained-Models) | Studies how pretrained SRL models generalize - and fail differently - across OntoNotes genres | Python, NLP |
| [Hotel management system](https://github.com/xiaoshanyichen/hotel-management-software-system) | A full-stack booking and management workflow with separate client and service layers | Java, Spring, Vue |

## How I like to work

```text
prototype the whole path  ->  measure the failure modes  ->  improve the system
```

- Make evaluation part of the architecture, not an afterthought.
- Build the "boring" infrastructure that makes experiments repeatable.
- Design around the person using the system and the constraints they actually have.

## Toolbox

**ML & research:** Python, PyTorch, Hugging Face Diffusers\
**Systems & backend:** C/C++, Java, Spring Boot, Redis, SQL, Docker, Linux\
**Product & reliability:** Flutter, Selenium, pytest/JUnit, Git

## Let's connect

I'm always interested in thoughtful conversations about generative modeling, reliable AI systems, accessibility, and the engineering that connects them.

[Email](mailto:ycao469@gatech.edu) · [LinkedIn](https://www.linkedin.com/in/yichen-cao-85815123a/)
