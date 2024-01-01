# 100 Days Of Code - Log

### Day 1: December 25, Monday

**Today's Progress**: Working out debounced text search in React. Also, first time using NextJS.

**Thoughts** I'm not used enough to using useCallback/useMemo. But at least it's clearer how they help solve re-render issues.

**Link(s) to work**
[Debounced user input in NextJS](https://github.com/eloyrobillard/nextjs-user-input)

### Day 2: December 26, Tuesday

**Today's Progress**: Created [DB in Supabase](https://supabase.com/dashboard/project/nuwidquxephmkslwzdxh/database/tables), and sent pokemons through with Prisma. Based on [this article](https://qiita.com/tomohiko_ohhashi/items/da804ed1f5870c9ce52d).

**TODO**: 
- API in Next
- Auth

**Thoughts**: I'm still unclear on how the whole FE+BE Next stuff will unwrap. Looking forward to tomorrow.

**Link(s)**: [day 2 commit](https://github.com/eloyrobillard/nextjs-user-input/commit/f193f6ad2bdc245d8445aed5bee2529dfe10e987)

### Day 3: December 27, Wednesday

**Today's Progress**
Made changes based on Magnus' [feedback](https://codereview.stackexchange.com/questions/288595/parsing-fetched-data-in-typescript/288603#288603):
- using typebox + typebox's TypeCompiler for JSON Schema and type validation
- removed `Result<T>` and custom JSON parsing

**TODO**: 
- Link API with FE
- Auth

**Link**: [day 3 commit](https://github.com/eloyrobillard/nextjs-user-input/commit/ef38c8f345a9b3962d83a1d3942284ba30f4cd2c), [r/codereview](https://www.reddit.com/r/codereview/comments/18ryom5/typescript_prisma_code_to_populate_db_with/)

### Day 4: December 28, Thursday

**Today's Progress**
Refactored based on [Netflix Clone React](https://github.com/NKDesign30/Netflix-Clone-React). 

**TODO**: 
- Link API with FE
- Auth

**Link**: [day 4 commit](https://github.com/eloyrobillard/nextjs-user-input/commit/81abb6a9d81d36455437d122de246c60168df4b7)

### Day 5: December 29, Friday

**Today's Progress**
Added grid for pokemon cards. Fixed, expanded, and further customized the ESLint config.

**Link**: [day 5 commit](https://github.com/eloyrobillard/nextjs-user-input/commit/e61d4d9c09eb55b4377dad2ed62184ca386791a7)

### Day 6: December 30, Saturday

**Today's Progress**
Re-populated DB with more complete pokemon data, including the sprites now shown in the UI.

**Link** [day 6](https://github.com/eloyrobillard/nextjs-user-input/commit/74008f6512cfe0965027e527caf7f3f454061797)

### Day 7: December 31, Sunday

**Today's Progress**

<details>
![image](https://github.com/eloyrobillard/100-days-of-code/assets/67062814/32ab08ad-8634-4b61-8430-bebdfaff42a8)
</details>

[Code Review](https://codereview.stackexchange.com/questions/288694/centering-ui-elements-with-flex-in-react)

**Link** [day 7](https://github.com/eloyrobillard/nextjs-user-input/commit/4fac9831a7f84c49ba6d4bdd9b16d6a7f07c356f)

### Day 8: January 1, Monday

**Today's Progress**

Added route/Link to page with pokemon details. Styling remains minimal at this point, and some data (abilities, forms) is missing.

**Link** [commit](https://github.com/eloyrobillard/nextjs-user-input/commit/de7794b7d660f223e9fd843cd0a58901794bc75c)
