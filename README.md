# Coach-Skills

Claude skills for running a personal training business: weekly client check-ins, red/orange/green triage, and a consistent review queue for the head coach. Built to improve itself with every use.

## Install (Claude web or desktop app)

You need a paid Claude plan (Pro or above).

1. **Check file creation is on**: Settings → Capabilities → **Create and edit files** (called *Code execution and file creation* in older versions). It's on by default; on a Team or business plan, an admin controls it.
2. **Connect Google Drive**: Customize → Connectors → Google Drive → Connect.
3. **Add these skills**: Customize → Plugins → **Add** → **Add marketplace** → enter `BobDeUncle/Coach-Skills`. Then install the **coach-skills** plugin.
4. **Stay up to date**: on the marketplace, switch on **Sync automatically**. New and improved skills then arrive on their own.

In Claude Code, install with `/plugin install coach-skills --marketplace BobDeUncle/Coach-Skills`.

## Skills

| Skill | What it does |
| --- | --- |
| `coach-requirements` | Interviews you about how you run check-in day, tests your traffic-light rules on real clients, and produces `coach-requirements.md` for building the check-in skills. |

### Running the requirements interview

Start a new chat, make sure Google Drive is switched on in the **+** menu, and say:

> Let's start the coach requirements interview.

It takes a few sessions. After each topic it gives you an updated `coach-requirements.md`: save it to your Downloads folder, replacing the old one. To carry on later, start a new chat, upload that file, and say "let's continue the coach requirements interview".

When it's finished, email the file to the person who set this up for you.
