# Changelog

## [[1.0.0]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v1.0.0)

- First release of **Mobioos Forge**.

## [[1.0.1]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v1.0.1)

- Update README.

## [[1.0.2]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v1.0.2)

- Changing some UI labels.
- Fixing bug with Feature Model Designer sometimes not allowing users to save valid nodes.
- Improve performances when computing code diagnostics (_Optional Feature Problem_ and _Dead Code_).

## [[1.0.3]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v1.0.3)

- Updating logo.

## [[1.0.4]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v1.0.4)

- Fixing issue with saving of feature model.
- Adding wizard mode for feature-mapping.
- Refactoring.
- Adding actions to feature-maps treeview.

## [[2.0.0]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.0.0)

- Feature Mapping process is now automatic.
- Adding `PENDING/VALIDATED` states to Markers/Maps.
- Complete revision of the *Mobioos Forge View*.
- Fixing bugs on the designer.
- Fixing bugs on the feature mapping process.
- Variants are now stored on folder `$HOME_FOLDER/mobioos-forge-customizations`.
- Replacements are now temporarily stored in folder `.mobioos-forge/replacements`.
- New usage of CodeLenses.

## [2.0.1]

- Adding link to the [list of tutorials](https://github.com/Mobioos/Mobioos-Forge-Tutorials) and to the extension on the [VScode marketplace](https://marketplace.visualstudio.com/items?itemName=Mobioos.mobioos-forge&ssr=false#overview).

## [[2.0.2]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.0.2)

- Validating a code-map containing a code-marker also validates the code-marker (if they have the same feature).
- Clicking on a File-Map on the Feature-Maps view opens the file in the editor.

## [[2.1.0]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.1.0)

- Fixing project not opening when creating a project on another folder.
- Optimizing derivation process.
- Removing old license management and using new authentication process.
- Adding more supported languages in the README.
- Using a `$HOME_DIR//mobioos` directory to store extension metadata and logs files.

## [[2.1.1]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.1.2)

- Updating README.

## [[2.1.2]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.1.2)

- Adjusting titles in README.
- New description for the extension.

## [[2.1.3]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.1.3)

- Fixing bug when adding twice a same marker (two marker on the exact same location and feature).
- Fixing error messages popping when using having forge installed on non-forge project.
- Fixing Feature-Maps view not showing maps on some sub-features.
- Fixing bug with anomaly detection & customization editor on big feature model.
- Fixing resource code-marker getting a range of 0 after validation process.
- Fixing replacement editor sometime getting out of sync when closing it.
- Improving feature mapping engine.
- Improving UI.

## [[2.1.4]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.1.4)

- Removing notifications popping when saving the feature model with the Feature model Designer.
- Fixing bug with mapping engine when mapping a local variable.
- Possibility to rename a project by right clicking on the project root (*forge activity > right click on project root > MF: Rename the project*)

## [[2.2.0]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.2.0)

- Users can now use major functionalities of forge without being logged (Only the derivation process requires the user to be logged).
- Adding two more panels to the **Forge Activity**:
  - **Mobioos Forge Projects** panel to let user easily create/open a Forge Project
  - **Welcome to Mobioos Forge** panel that lists several links to guide users through your usage of Mobioos Forge
- Fixing a bug with the Mapping process engine.
- Automatically opening de feature model designer when opening a forge project through the forge activity.

## [[2.2.1]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.2.1)

- Fixing bug with feature model designer when changing the children rule of a parent feature.
- Fixing inconsistances in samples' feature models.
- Adding an "Open Samples" button when no project is open.
- Showing an error message when trying to save a customization scenario with wrong file resource paths.

## [[2.2.2]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.2.2)
- Fixing zoom on the Feature Model Designer (with mouse wheel and top bat dropdown list).
- Adding dragging ability to the Feature Model Designer.
- Fixing the Customization process sometimes not creating the required folders leading into a failure during the creation of the customized application.
- Fixing the Customization process sometimes preventing the creation of the customized application because of un-validated markers (despite them being validated).into a failure during the creation of the customized application.
- Adding loading modals to the Customization Editor to warn when it is loading.
- Adjusting positions displayed in the Feature-Maps view.

## [[2.2.3]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.2.3)
- Improving loading time of Forge projects.

## [[2.2.4]](https://github.com/Mobioos/Mobioos-Forge/releases/tag/v2.2.4)
- Adding .mobioosignore functionality.
- Fixing bug of extension sometimes not loading correctly at startup.
- Improving maps tracking algorithm when editing code.
- Adding CTRL+S hotkey to save the feature model in the designer.
- Improving code tracking algorithm.
- Adding possibility to add/remove several file-markers at once.
- Not using markers files anymore (`~$PROJECT_NAME.functionalities.maps.forge` and `~$PROJECT_NAME.resources.maps.forge`)