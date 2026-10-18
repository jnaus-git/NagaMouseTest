# NagaMouseTest

Browser-based tester and typing practice for Razer Naga side-button keybinds.

## Open the app

Open [`src/nagatest.html`](src/nagatest.html) in a browser. No build or package installation is required.

## Free button test

Choose the side plate installed on the mouse: 12-button, 6-button, or 2-button. Focus the test field and press a side button to see its keyboard output and highlight the matching tile.

The 6-button plate is arranged like the physical panel:

```text
1  2  3
6  5  4
```

## Configure Synapse mappings

Open **Settings: Synapse mappings** and choose **Edit mappings** to prevent accidental changes. Click a mapping field or grid tile, then press the corresponding Naga side button. Its keyboard output is saved for that button. You can also type a mapping directly into a field.

Mappings are saved in the browser's local storage, separately for each plate. The page cannot read settings directly from Razer Synapse; enter or assign the keys configured there.

## Typing lessons

Lessons use the 6-button plate and the configured mappings for physical buttons 5 and 2. The focused lesson view shows the sequence and highlights the button to press. Use **Repeat lesson**, **Next lesson**, and **Exit lesson** to control practice.

- **Lesson 1:** Practice each home-row key individually, then repeat it up to four times.
- **Lesson 2:** Practice mixed combinations of the two home-row keys, up to four presses.
- **Lesson 3: Home row game:** Complete random five-key sequences during a 30-second round. The timer starts on the first key press. Correct presses count toward the score; wrong presses do not advance the sequence. At the end, the app shows accuracy and saves the best correct-press score in local storage.
