# 📝 List Compose

- Discipline: Programming for Mobile Devices
- Teacher: Junio Moreira
- Student: João Augusto Marciano Silva
- Final date: 07/11/2025

## Application Operation

### Light Mode

| Onboarding Screen | List of Items (Default) | Expanded Item (Animation) |
|:---:|:---:|:---:|
| <img height="500" alt="Onboarding Light" src="https://github.com/user-attachments/assets/b6ceab09-dd6d-4b69-b678-76d253dcd4e7" /> | <img height="500" alt="List Screen Light" src="https://github.com/user-attachments/assets/6eda0533-b766-4a08-86e7-12985f2bea40" /> | <img height="500" alt="Expanded Item Light" src="https://github.com/user-attachments/assets/145b481c-2e04-4afe-8971-7a4e3303a679" /> |

### Dark Mode

| Onboarding Screen | List of Items (Default) | Expanded Item (Animation) |
|:---:|:---:|:---:|
|<img height="500" alt="Onboarding Dark" src="https://github.com/user-attachments/assets/44eb7ac6-afab-44df-9f9b-f3801f86dd2e" /> | <img height="500" alt="List Screen Dark" src="https://github.com/user-attachments/assets/16d22117-1e67-4d19-949d-866f5875aab8" /> | <img height="500" alt="Expanded Item Dark" src="https://github.com/user-attachments/assets/b4e645b9-430a-4f34-a149-6b081155d783" /> |

## Features

- Practical implementation of fundamental Jetpack Compose concepts following the official Android Codelab.
- Features two main state-controlled screens:
    - **Onboarding Screen:** Welcome screen that persists the user's decision ("Continue" button) even during screen rotation (using `rememberSaveable`).
    - **Greetings Screen:** Main screen containing a list of cards.
- Uses `LazyColumn` for efficient rendering of a long list (100 dynamically generated items).
- **Fluid Animations:** - Each list item is expandable.
    - Upon clicking the icon, the content expands using `animateContentSize` with spring physics (`spring` animation) for a smooth visual effect.
- **Design and Themes:**
    - Full implementation of Material Design 3.
    - Native support for Light and Dark themes, featuring a custom color palette (Navy, Blue, Chartreuse).
    - Text and buttons adapt automatically to the device's accessibility and theme settings.
- **Dynamic Content:**
    - Displays custom "Lorem Ipsum" text (Silvio Santos Ipsum) when expanding the cards.
    - Dynamic icons that switch between "Expand Less" and "Expand More" based on the card's state.

## Download

APK
