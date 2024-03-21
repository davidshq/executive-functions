# Simpleology Simplified

## Overview
In the main [Simpleology](simpleology.md) document there is a flowchart that shows the workflow one progresses through when using Simpleology, it's a bit overwhelming, this document focuses on providing a simplified view which highlights the areas I'm particularly interested in.

## Simplified Flowchart
```mermaid
flowchart TD
    subgraph A[A Morning Brainstorm]
        a1[Capture everything on mind]
    end
    subgraph B[Stay Focused]
        b1[Review strategic goals] -->
        b2[Enter tasks, ideas]
    end
    subgraph C[Recurring Tasks]
        c1[Review existing recurring tasks/systems]
        c2[Create new recurring tasks/systems]
    end
    subgraph G[Decide for each task]
        gg1[Edit]
        gg2[Do]
        gg02[Delegate]
        gg03[Schedule]
        gg4[Dump]
    end
    subgraph H[Prioritize]
        h1[Free Form or HIME]
    end
    subgraph I[Daily Targets]
        i21[Complete]
        i22[Delegate]
        i23[Move to Project]
        i24[Move to List]
        i25[Do Later]
        i26[Set Reminder]
        i27[Subtasks]
        i28[Comments & Attachments]
        i29[Edit]
        i30[Delete]
    end
    A --> B
    B --> C
    C --> G
    G --> H
    H --> I
```