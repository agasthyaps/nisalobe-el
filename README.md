# ELCurriculum — EL Education ELA Curriculum (Grades 6–8)

**Subject:** English Language Arts (ELA)
**Grades:** 6, 7, 8  **Modules per grade:** 4  **Units per module:** 3 + performance task
**Total lessons:** ~450  **Materials per lesson:** 8–15 files

## Grade/Module Map

| Grade | M1 | M2 | M3 | M4 |
|-------|----|----|----|----|
| **6** | Greek Mythology | Critical Problems and Design Solutions | American Indian Boarding Schools | Remarkable Accomplishments in Space Science |
| **7** | The Lost Children of Sudan | Epidemics | The Harlem Renaissance | Plastic Pollution |
| **8** | Folklore of Latin America | Food Choices | Voices of the Holocaust | Lessons from Japanese American Internment |

## Navigation
When calling knowledge tools (list-expertise-files, read-expertise-file), always use plain forward slashes as path separators. For example: 6/Module3/Unit2/lesson.md. Never URL-encode path segments — do not use %2F or any other percent-encoding in paths.

example interaction:
User: “Give me an overview of Grade 8, Module 2, Unit 2, Lesson 2.”
Nisa:
List 8/ → find ELA_G8M2
List 8/ELA_G8M2/ → find G8M2_Unit_2
List 8/ELA_G8M2/G8M2_Unit_2/ → find G8M2U2_Lesson_2
List 8/ELA_G8M2/G8M2_Unit_2/G8M2U2_Lesson_2/ → find _OVERVIEW.md
Read 8/ELA_G8M2/G8M2_Unit_2/G8M2U2_Lesson_2/_OVERVIEW.md
Return overview

## Common Use Cases
- Find a lesson on a specific topic → check module map above, then module `_OVERVIEW.md`
- Find all materials for a lesson → lesson `_OVERVIEW.md` lists all files with descriptions
- Find assessments → look for files with `Assessment`, `Rubric`, or `AO` in name
- Find ELL supports → files with `ELL` in name or `_ELL` suffix
- Find family/homework materials → files with `HR` or `Family` in name

## File Naming Convention
`G{grade}M{mod}U{unit}L{lesson}[-suffix]-{ContentType}_{Audience}.md`
Audience codes: Teacher, Student, Class, Family, ELL, LD, Group
