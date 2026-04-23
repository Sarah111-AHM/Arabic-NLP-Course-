# NLP Course (Arabic) – Complete Resources & Notes

This repository is a personal compilation of all materials, links, notes, and clarifications from the NLP course taught by:

- **Rayene Bech** – [LinkedIn](https://linkedin.com/in/rayene-bech)
- **Muhanad Tuameh** – [LinkedIn](https://linkedin.com/in/muhanad-tuameh)
- **Mohammed Besher Al-Kurdi** – [LinkedIn](https://linkedin.com/in/mohammed-besher-al-kurdi)

All rights of the original course materials belong to their respective owners. This repo only provides links and my personal notes.

---

## Official Course Links

| Type | Link |
|------|------|
| YouTube Playlist (recorded lectures) | [https://www.youtube.com/playlist?list=PL3k0VOxVMksZVQAXDf52y6h8f7kpbCKVb](https://www.youtube.com/playlist?list=PL3k0VOxVMksZVQAXDf52y6h8f7kpbCKVb) |
| Google Drive Folder (slides & files) | [https://drive.google.com/drive/folders/1169ITtuLV3kRGym3ctiTxG22upSpJyn-](https://drive.google.com/drive/folders/1169ITtuLV3kRGym3ctiTxG22upSpJyn-) |
| Google Meet Link (all sessions) | [https://meet.google.com/vtb-nuio-oiw](https://meet.google.com/vtb-nuio-oiw) |

---

## Lectures List (with YouTube Live links)

| # | Topic | YouTube Live Link |
|---|-------|-------------------|
| 1 | PyTorch & Model Training | (in playlist) |
| 2 | Activation Functions & Optimization | [https://youtube.com/live/xYU5w7R0zlA](https://youtube.com/live/xYU5w7R0zlA) |
| 3 | Bag of Words & Embeddings | [https://youtube.com/live/a_3IivjqwE8](https://youtube.com/live/a_3IivjqwE8) |
| 4 | Recurrent Neural Networks (RNNs) | [https://youtube.com/live/ZKhoq1mBjPs](https://youtube.com/live/ZKhoq1mBjPs) |
| 5 | Attention Mechanism | [https://youtube.com/live/Mv8ECmVpHHI](https://youtube.com/live/Mv8ECmVpHHI) |
| 6 | Transformers | [https://youtube.com/live/5X7ojtiyBJ4](https://youtube.com/live/5X7ojtiyBJ4) |
| 7 | Tokenization | [https://youtube.com/live/W5O8p9M_TaA](https://youtube.com/live/W5O8p9M_TaA) |
| 8 | Retrieval-Augmented Generation (RAG) | [https://youtube.com/live/u1NLc3PMBSY](https://youtube.com/live/u1NLc3PMBSY) |
| 9 | Reinforcement Learning (RL for LLMs) | [https://youtube.com/live/9dNrZd0mAIg](https://youtube.com/live/9dNrZd0mAIg) |

### Recorded lectures on Google Drive (after sessions)
- Lecture 7 (Tokenization): [Link](https://drive.google.com/file/d/1F0mFZRsiB2YhWTVue3ZIJkPjsruShJqj/view?usp=drive_link)
- Lecture 8 (RAG): [Link](https://drive.google.com/file/d/1QhMJMGYZCi47hdXGkdBwl0YnIVv0dZbU/view?usp=drive_link)
- Lecture 9 (RL): [Link](https://drive.google.com/file/d/1pmNWqHqIn7H5VlvxS1FqGqnnC_L3_BNS/view?usp=drive_link)

### Extra practical session (coding from scratch using L-HSAB dataset)
- YouTube Live: [https://youtube.com/live/wMAJ95Q6WKo](https://youtube.com/live/wMAJ95Q6WKo)
- **Date:** Sunday, 15 March 2026, 9:00–11:00 PM (Damascus time)

---

## Assignments (GitHub Classroom)

| Assignment | Link | Status |
|------------|------|--------|
| Assignment 1 | [https://classroom.github.com/a/QmO9y9M1](https://classroom.github.com/a/QmO9y9M1) | ✅ |
| Assignment 2 | [https://classroom.github.com/a/7iKzuPbM](https://classroom.github.com/a/7iKzuPbM) | ✅  |
| Assignment 3 | [https://classroom.github.com/a/BJ3Sgx44](https://classroom.github.com/a/BJ3Sgx44) | ✅  |
| Assignment 4 | [https://classroom.github.com/a/mGj8qRtC](https://classroom.github.com/a/mGj8qRtC) | ✅  |
| Assignment 5 | [https://classroom.github.com/a/kNsr2bwE](https://classroom.github.com/a/kNsr2bwE) | ✅  |
| Assignment 6 (Final) | [https://classroom.github.com/a/b6TnQ6pb](https://classroom.github.com/a/b6TnQ6pb) | ✅  |

> **Important:** Official solutions will be posted 3 weeks after each assignment deadline.  
> If you haven't shared your GitHub username with the instructors, use this form: [https://forms.gle/2Vt2hNkY5G3EUWB98](https://forms.gle/2Vt2hNkY5G3EUWB98)  
> Help video on how to submit assignments: [https://youtu.be/BlcDQU_Nv0M](https://youtu.be/BlcDQU_Nv0M)

---

## Important Clarifications & Q&A (from course discussions)

1. **Correction about Softmax + Loss formula (Lecture 2)**  
   The slide initially showed a `+` sign between Softmax and Loss, implying simple addition. This is **incorrect**. The combined loss is formed differently (mathematical details not required, but the instructor corrected it).

2. **CBOW and word order**  
   *Q: Does CBOW know the order of context words?*  
   *A:* No. CBOW treats context words as a "bag" – order does not matter. That's why it's called *Continuous Bag of Words*.

3. **Output matrix in word2vec**  
   *Q: Is the output matrix updated during training?*  
   *A:* Yes. Both input and output matrices start random and are updated via backpropagation. After training, only the input matrix is used to get word embeddings; the output matrix is discarded.

4. **Are embeddings a form of encryption?**  
   *Q: Can word embeddings be used for encryption?*  
   *A:* No. Although embeddings convert text to numbers, they are not secure enough. Classical encryption methods are far more reliable and efficient.

5. **Tokenizer parameter issue in Trainer (Hiba's question)**  
   Some participants faced an error where the `tokenizer` parameter is no longer recognized in modern `Trainer` versions. The solution is to handle tokenization as a preprocessing step and use `data_collator` to batch properly.

---

## Final Project (Optional)

- **Form to apply:** [https://forms.gle/1cBG7wWopC3oMiSj8](https://forms.gle/1cBG7wWopC3oMiSj8)
- **Project ideas discussion (from lecture 9):** [https://youtube.com/live/9dNrZd0mAIg](https://youtube.com/live/9dNrZd0mAIg)
- **Coordination board (Excalidraw):** [https://excalidraw.com/#room=9592004574796ef6d9a7,kCfnoC7XiY-FZw3eWHVGnA](https://excalidraw.com/#room=9592004574796ef6d9a7,kCfnoC7XiY-FZw3eWHVGnA)

> You can work alone or with a partner. Both members must fill the form and mention each other's GitHub username.

---

## Recommended Reading

- Meta research paper on Hallucination in LLMs (shared by Ibrahim Mayhoub) – highly recommended for understanding model faithfulness. (Link to be added if available)

---

## Dataset used in practical session

**L-HSAB: First Arabic Levantine Hate Speech Dataset**  
[https://github.com/Hala-Mulki/L-HSAB-First-Arabic-Levantine-HateSpeech-Dataset/blob/master/Dataset/L-HSAB](https://github.com/Hala-Mulki/L-HSAB-First-Arabic-Levantine-HateSpeech-Dataset/blob/master/Dataset/L-HSAB)

---

## Acknowledgments

Special thanks to **Rayene Bech**, **Muhanad Tuameh**, and **Mohammed Besher Al-Kurdi** for organizing and delivering this excellent course. Thanks also to all participants for their questions and contributions.

This repository is maintained for personal revision and to help fellow students. If any instructor requests removal of certain content, I will comply immediately.

---

*Last updated: April 2026*
