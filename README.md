# DS Wizard - diagrams

[![Creative Commons License](https://i.creativecommons.org/l/by-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nd/4.0/)


Diagrams describing visually how the [Data Stewardship Wizard](https://ds-wizard.org) works

## Usage

You may use easily the PNG files located in the `/png` folder in reasonable pixel size. If you need higher resolution, you can create better one using vector graphics from `/svg`.

Note that all files are published under [CC BY-ND 4.0](license) license that **forbids** derivatives of our work and you must indicate author (**ds-wizard team**, Marek Suchánek namely)! You can propose changes using GitHub issues and we can help you with approved customization. It helps us to avoid misunderstandings of the Wizard and also maintain the user's experience...

## Diagrams

There are following diagrams:

- `process_overview` = overall process of using the Wizard using simplified overview (no details)
- `dsw_workflow` = detailed view on the workflow in the Wizard that composes following parts into one diagram:
  - `dmp_export` = process of exporting a Data Management Plan from a questionnaire by selecting a template and format
  - `km_editor_changes` = a Knowledge Model can be edited by creating three types of changes: add, edit, and delete, then a new version can be published
  - `km_hierarchy` = Knowledge Models can customize others forming a tree structure with a generic KM as a root
  - `km_migration` = how changes can be propagated from parent KM to child KM using migration process
  - `km_structure` = how Knowledge Models and Questionnaires are structured (chapters, questions, followup questions) and what information can be attached to a question (references, experts, tags, and integrations)
  - `questionnaire` = the loop of filling the questionnaire generated from a KM together with integrations, metrics, and evaluations

## License

This work is licensed under a [Creative Commons Attribution-NoDerivatives 4.0 International License](http://creativecommons.org/licenses/by-nd/4.0/)
