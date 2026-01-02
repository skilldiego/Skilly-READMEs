**Ship of Harkinian (SoH)** is a community-developed, reverse-engineered PC port of *The Legend of Zelda: Ocarina of Time*. Unlike emulation, SoH runs natively on modern hardware, enabling widescreen support, high frame rates, modding, and other enhancements.

This guide details the optimal setup process, from installation to configuration.

> **Note:** This guide is based on the **Copper Bravo (9.1.1)** release, on Windows and using an Xbox One Controller.


# Initial Setup
1. Find or dump a supported **Legend of Zelda: Ocarina of Time (OoT)** ROM.
1. Download the latest release of **Ship of Harkinian (SoH)** for your OS from GitHub.
1. Extract the downloaded ZIP file to a folder.
1. Move the OoT ROM into the extracted SoH folder.
1. Start the `soh` binary (executable).
1. When prompted to generate OTR files, click **Yes**.
1. Select your detected ROM and click **Yes**.
1. Wait for the generation process to complete. If asked to add another ROM, click **No**.
1. Ship of Harkinian will start running Ocarina of Time on your machine.

# Optimal Controller Setup
Ship of Harkinian supports most controllers (Xbox, PlayStation, Switch) out of the box. If you do not have a dual analog controller, skip these steps.

The configuration below binds the buttons to mimic the physical layout of **Ocarina of Time on the GameCube**. Specifically, mapping **N64 B** to **Xbox X** replicates the angle of the GameCube's B button relative to A. It also moves C-buttons to the remaining face buttons to free up the Right Stick for modern camera control.

To configure and remap buttons:

1. Press **Esc** to open the on-screen menu bar.
1. Click on **Settings** in the top bar, then select **Controls**.
1. Ensure your controller is selected in the dropdown menu.
1. **Remap Buttons:** SoH auto-maps controllers, but the following layout is optimized for modern dual-stick gameplay (using an Xbox controller). Use the **X** icon to remove bindings and the **+** icon to add new ones.

    | N64 Button | Xbox Input |
    | :--- | :--- |
    | **A** | A |
    | **B** | X |
    | **Start** | Menu |
    | **L** | LB |
    | **R** | RT |
    | **Z** | LT |
    | **C-Up** | *Unbind* |
    | **C-Down** | RB |
    | **C-Left** | Y |
    | **C-Right** | B |

1. **Additional Control Settings:** Scroll down in the Controls window to configure the following:
    *   **Ocarina Controls:** Enable **Dpad Ocarina Playback**.
    *   **Camera Controls:** Enable **Right Stick Aiming** and **Allow moving while in first-person mode**.
    *   **Third-Person Camera:** Enable **Free Look** (allows right-stick camera control).
    *   **Inversion:** (Optional) Disable **Invert Aiming Y Axis** and **Invert Z-Weapon Aiming Y Axis**.
1. **Navi Fix:** Since **C-Up** was unbound, you must enable an enhancement to talk to Navi.
    *   Close the **Controls** window.
    *   Go to **Enhancements** > **Quality of Life**.
    *   Enable **Answer Navi Prompt with L Button**.