# Onboarding Screens

A collection of mobile UI screen designs for an onboarding and account-creation flow.

## Overview

This package contains four high-resolution PNG screens that can be used as:

- UI/UX design references
- Mobile app onboarding mockups
- Frontend implementation references
- Design handoff assets
- Product or prototype documentation

> **Note:** This ZIP contains image assets only. It does not include application source code, dependencies, or a runnable mobile/web project.

## Screens Included

| Screen | File | Dimensions |
|---|---|---:|
| Onboarding | `Onboarding screens.png` | 1206 × 2622 px |
| Choose Role | `choose role screen.png` | 1206 × 2622 px |
| Create Account | `create account.png` | 1206 × 2622 px |
| Login | `login screeen.png` | 1206 × 2622 px |

### 1. Onboarding Screen

`Onboarding screens.png`

The introductory screen(s) for presenting the product or service to a new user before account setup.

### 2. Choose Role Screen

`choose role screen.png`

A role-selection step where the user can choose the appropriate account/user type before continuing.

### 3. Create Account Screen

`create account.png`

The registration screen used to collect the information required to create a new account.

### 4. Login Screen

`login screeen.png`

The returning-user authentication screen for signing in to an existing account.

## Suggested User Flow

The screens can be implemented in the following sequence:

```text
Onboarding
    ↓
Choose Role
    ↓
Create Account
    ↓
Login
```

The exact navigation behavior can be adjusted according to the application requirements. For example, an existing user may navigate directly from onboarding to Login, while a new user can continue through role selection and account creation.

## Folder Structure

After extracting the ZIP, the relevant structure is:

```text
ONBOARDING_SCREENS/
├── Onboarding screens.png
├── choose role screen.png
├── create account.png
└── login screeen.png
```

The ZIP may also contain `__MACOSX` metadata files created by macOS. These files are not required for the UI assets and can be ignored.

## Design Handoff

When implementing these screens in a mobile application:

1. Use the PNGs as visual references rather than as application logic.
2. Recreate text, buttons, input fields, icons, and navigation using native UI components.
3. Preserve the intended spacing, alignment, typography, and visual hierarchy.
4. Make the layouts responsive for different device sizes.
5. Add appropriate validation and error states to interactive fields.
6. Connect buttons to the application's navigation and authentication logic.
7. Test the screens on both smaller and larger mobile displays.

## Implementation Notes

These assets are suitable for implementation in frameworks such as:

- Flutter
- React Native
- Android (Kotlin/Jetpack Compose or XML)
- iOS (SwiftUI or UIKit)
- Web/mobile-responsive HTML, CSS, and JavaScript

No framework is specified by the asset package, so the implementation technology should be selected based on the target application.

## Asset Specifications

- **Format:** PNG
- **Resolution:** 1206 × 2622 pixels per screen
- **Color mode:** RGBA
- **Number of primary screens:** 4

## File Naming

One original filename is spelled `login screeen.png`. If these assets are being integrated into a software project, it may be preferable to rename it to:

```text
login-screen.png
```

Similarly, for consistent naming, the other files could be normalized to:

```text
onboarding-screen.png
choose-role-screen.png
create-account.png
login-screen.png
```

## Getting Started

### 1. Extract the ZIP

Extract `ONBOARDING_SCREENS.zip` into your project or design-assets directory.

### 2. Review the screens

Open the PNG files in an image viewer or design tool such as Figma, Sketch, Adobe XD, or Photoshop.

### 3. Recreate the UI

Use the screens as the visual source of truth when building the corresponding application screens.

### 4. Connect navigation

Implement the onboarding flow and connect each action to the appropriate next screen.

### 5. Add application logic

For a production application, add:

- Form validation
- Authentication
- Account creation
- Role selection persistence
- Loading states
- Error handling
- Secure credential handling
- Accessibility support

## License

No license information is included in the ZIP. If these designs or assets are being distributed or used in a commercial project, confirm that you have the necessary rights and permissions.

## Status

**Design assets / UI reference package**

This repository/package currently contains visual screen assets and does not contain a runnable application.
