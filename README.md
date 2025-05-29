# Espanso Configuration - base.yml

This repository contains `base.yml`, a configuration file for Espanso, a cross-platform text expander. This file defines a collection of custom text replacement snippets to improve productivity and consistency.

## Overview of Snippets

The `base.yml` file includes a variety of snippets, categorized as follows:

*   **Simple Text Replacements:** Common phrases and terms are shortened with easy-to-remember triggers. For instance, `jggm` expands to "Good morning".
*   **Acronyms and Initialisms:** Provides quick expansions for frequently used acronyms, such_as `esd` becoming "Enterprise Service Desk (ESD)".
*   **Dynamic Content:**
    *   **Dates:** Triggers like `jgdate` (current date), `jgday` (current day of the week), `jgtomorrow`, and `jgyesterday` insert formatted dates.
    *   **Shell Commands:** The `:shell` trigger can execute and display the output of shell commands.
*   **Forms:**
    *   The `SBI - ` or `sbi - ` trigger launches a form for structured feedback, prompting for "Employee Name," "Feedback Type," "Situation," "Behavior," and "Impact."
*   **Contact Information:** Shortcuts for frequently used email addresses and phone numbers.
*   **Cybersecurity:** A set of snippets for common phrases, email distribution lists, and recurring cybersecurity-related messages.
*   **Microsoft Products:** Shortcuts for names like "Microsoft", "Power Platform", "Power Automate", etc.
*   **Images & Emojis:**
    *   Various triggers like `jgbeer` and `jgnnn` insert images directly.
    *   The `jgmeatball` snippet uses a Python script to copy the NASA "meatball" logo to the clipboard, allowing it to be pasted into applications that support image pasting.
    *   A collection of emoji snippets (e.g., `jglove` for ❤️, `jgrocket` for 🚀).
*   **AI-Related Information:** Snippets to quickly share information about tools like `LibreChat`, `ChatGSFC`, and NASA's guidance on Generative AI.
*   **Daily Schedule (`jgdaily`):**
    *   This is a more advanced snippet that runs a Python script.
    *   The script generates a daily schedule summary including:
        *   The current date and pre-defined work hours.
        *   A list of meetings scheduled for the current day of the week (meetings are defined within the script).
        *   A "ToDo" list extracted from the most recent day's entry in a local Markdown file (`C:\Users\jrgarrig\Documents\Obsidian Vault\review.md`).

## Espanso

Espanso is an open-source, cross-platform text expander that helps you save time by automating repetitive typing tasks. You can learn more about Espanso and its configuration at [https://espanso.org/docs/](https://espanso.org/docs/).

## Usage

To use these snippets, you need to have Espanso installed and this `base.yml` file placed in the Espanso user configuration directory. Refer to the official Espanso documentation for installation and configuration instructions.
