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
