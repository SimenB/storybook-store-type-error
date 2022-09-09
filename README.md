1. `yarn`
2. `yarn build`

```
node_modules/@storybook/api/dist/types/index.d.ts:5:34 - error TS2307: Cannot find module '@storybook/core-common' or its corresponding type declarations.

5 import type { DocsOptions } from '@storybook/core-common';
                                   ~~~~~~~~~~~~~~~~~~~~~~~~

node_modules/@storybook/api/dist/types/lib/stories.d.ts:3:34 - error TS2307: Cannot find module '@storybook/core-common' or its corresponding type declarations.

3 import type { DocsOptions } from '@storybook/core-common';
                                   ~~~~~~~~~~~~~~~~~~~~~~~~

node_modules/@storybook/store/dist/types/StoryStore.d.ts:32:54 - error TS2307: Cannot find module 'lib/addons/dist/types/types' or its corresponding type declarations.

32     storyIdToEntry(storyId: StoryId): Promise<import("lib/addons/dist/types/types").IndexEntry>;
                                                        ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Found 3 errors in 3 files.

Errors  Files
     1  node_modules/@storybook/api/dist/types/index.d.ts:5
     1  node_modules/@storybook/api/dist/types/lib/stories.d.ts:3
     1  node_modules/@storybook/store/dist/types/StoryStore.d.ts:32
```
