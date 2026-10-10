# Quiz Challenge Bangladesh Website

This repository contains the main website for https://quizchallengebd.com/, including educational library pages, study guides, policies, and website-level quiz copies.

## Four-repository organization

| Repository | Purpose | Add new quiz content here |
|---|---|---|
| [quiz-challenge-bangladesh](https://github.com/Aliakbar1974/quiz-challenge-bangladesh) | Bangladesh Studies and English Vocabulary quizzes | `Bangladesh-Quiz-NN/` or `Vocabulary-Quiz-NN/` |
| [English-Grammar](https://github.com/Aliakbar1974/English-Grammar) | English Grammar, organized by Level and Chapter | `Level-NN/Chapter-NNNN/` |
| [General-Knowledge](https://github.com/Aliakbar1974/General-Knowledge) | World History, Geography, ICT, Space, Science, and other GK topics | `Subject-Quiz-NN/` |
| [Quiz-Challenge-Bangladesh-Website](https://github.com/Aliakbar1974/Quiz-Challenge-Bangladesh-Website) | Main website, category listings, study guides, and policies | Website pages and intentional website-specific files only |

## Future quiz workflow

1. Create the quiz in its subject's repository; do not mix categories across repositories.
2. Give the quiz the next unused number and include a working `index.html`.
3. Keep the quiz's JavaScript, CSS, images, and sounds with that quiz unless the established project deliberately uses shared assets.
4. Check the corresponding GitHub Pages quiz URL.
5. Open the matching library page on quizchallengebd.com and confirm that the new quiz appears. Library pages use the source repositories' folder listings where automatic discovery is enabled.

## Website library pages

- Bangladesh: https://quizchallengebd.com/bangladesh-quizzes.html
- Vocabulary: https://quizchallengebd.com/vocabulary-quizzes.html
- English Grammar: https://quizchallengebd.com/english-grammar-quizzes.html
- General Knowledge: https://quizchallengebd.com/general-knowledge-quizzes.html

## Important

Do not copy the same quiz into multiple repositories just to make it appear in a library. Keep one source of truth for each quiz category. The main website should link to quizzes from their correct repository. When changing quiz folder naming conventions, update the matching library discovery script too.
