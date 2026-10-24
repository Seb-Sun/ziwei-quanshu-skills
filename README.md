# Ziwei Quanshu Skills

[简体中文](README.zh-CN.md)

Source-grounded prompts and portable skills for studying **Zi Wei Dou Shu Quan Shu (《紫微斗數全書》)** with ChatGPT and DeepSeek. The workflow checks rule conditions, separates chart facts from traditional interpretations, and keeps references traceable.

**Bring your own source.** This repository contains prompts, workflow instructions, and paraphrased method notes. It does not distribute the book, scans, a full transcription, or personal chart records.

## What it does

- Checks each relevant condition as satisfied, not satisfied, or unknown.
- Separates a basic star combination from a complete pattern and its interpretation.
- Keeps natal charts, major periods, minor periods, and annual factors distinct.
- Explains a supported main interpretation, its evidence, and possible manifestations in plain language instead of repeating generic uncertainty statements.
- Ends every response with a plain-language summary.
- Preserves ambiguities instead of inventing thresholds, scores, probabilities, or missing rules.

This is a traditional-text study and interpretation workflow, not a validated prediction system or a complete chart-calculation engine.

## Choose a package

| Package | Entry point | Copy-and-paste prompt |
| --- | --- | --- |
| ChatGPT | [SKILL.md](skills/ziwei-quanshu-chatgpt/SKILL.md) | [PROMPT.md](skills/ziwei-quanshu-chatgpt/PROMPT.md) |
| DeepSeek | [SKILL.md](skills/ziwei-quanshu-deepseek/SKILL.md) | [PROMPT.md](skills/ziwei-quanshu-deepseek/PROMPT.md) |

Each package includes its own `references/` directory and can be copied independently. The skill bodies and prompts are in Chinese. This English README introduces the project; it is not an English translation of the skills.

## Quick start

1. Choose a package and open its `PROMPT.md`.
2. Paste the text after the separator into a new conversation.
3. Provide relevant pages or excerpts from a lawfully obtained copy, with the title, edition, and page-number convention. Start with only the material needed for the question.
4. Provide an existing, verifiable chart if the question requires one. Use the package's `references/input-schema.md` as a guide; unrelated birth details are unnecessary.
5. Ask a focused question. The assistant should state what it actually read before applying source-dependent rules.

In an environment that explicitly supports `SKILL.md`, load the complete selected package using that environment's supported mechanism. Uploading a directory or ZIP does not, by itself, mean that every file has been read. File access, vision, retrieval, and execution depend on the actual environment; these prompts do not grant those capabilities.

Without source pages, the assistant can explain the included method notes and organize questions. It must not claim to have checked the book or use the notes as a complete rulebook.

## Source edition and page references

The paraphrased notes were prepared with reference to a 1989 edition of 《紫微斗數全書》, attributed on its title information to 陳希夷, edited by 梁湘潤, and published by 台灣文源書局有限公司. In the working scan used to prepare the notes, PDF page numbers counted from the cover, and the scan contained 334 pages.

Page numbers in the notes are **locators for that scan**, not universal page numbers. If you use another copy or edition, establish the correspondence first. A user must supply the relevant material before the assistant can claim direct verification. These notes are selective paraphrases, not a replacement for the book or a verified edition of its text.

## Example request

> Please use only the source pages and chart I supply. Identify the supported main interpretation, show the relevant conditions and evidence, and distinguish traditional interpretation from modern examples. Explain the concrete unknowns once, and finish with a plain-language summary.

The project does not embed a particular person's chart, major-period starting age, or choice between disputed calculation conventions. A user's chosen convention must be recorded as such, rather than silently treated as a proven source rule.

## Publishing and contributing

Submit improvements to the workflow, paraphrases, or synthetic examples. Do not add complete book transcriptions, scanned pages, private charts, conversation exports, credentials, or machine-specific paths. Independently check any submitted source claim.

To publish this prepared folder through GitHub's website: create a repository, use **Add file → Upload files**, and upload the folder's contents while preserving the `skills/` structure. Read the file list before committing. `.gitignore` is a Git exclusion mechanism; it does not inspect or prevent manual browser uploads. Check Markdown files as well as media for third-party content.

The prompts were prepared with AI assistance. No systematic evaluation against specific ChatGPT or DeepSeek model versions has been completed. The project is independent and is not affiliated with OpenAI, DeepSeek, or the book's publisher.

## License and source rights

Project-original material is offered under the [MIT License](LICENSE), only to the extent contributors hold the necessary rights. The license grants no rights in the source book or other third-party material. See [NOTICE.md](NOTICE.md) for the distribution boundary. Omitting scans does not, by itself, establish that every quotation or paraphrase is legally cleared; review additions before publishing.
