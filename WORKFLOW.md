# NorthBridge-Inbox Workflow

NorthBridge-Inbox is the public bridge between North and Forge.

## Rules

- This repository only carries workflow notes and approved handoffs.
- No private King-Wolf manuscript, dossier, or unpublished canon content may be copied here.
- Chat is discussion only.
- Approved Markdown in the private King-Wolf repository is canon.

## Roles

- Chevaughn: final approval authority.
- North: creative lead and handoff author.
- Forge: repository manager.

## Triggers

- `North, close the session` publishes a handoff to `Inbox/Pending/`.
- `Forge, process the inbox` reads `Inbox/Pending/`, updates repositories, and archives the processed handoff.
- `Forge, audit the repository` performs a read-only audit.

## Public Bridge Layout

- `README.md`
- `WORKFLOW.md`
- `Templates/TASK_TEMPLATE.md`
- `Inbox/Pending/`
- `Inbox/Applied/`
- `Inbox/Archived/`

## Operating Notes

- Process only approved content.
- Keep the public bridge free of private canon.
