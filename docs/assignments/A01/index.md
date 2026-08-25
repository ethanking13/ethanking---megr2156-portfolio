# A1 – Build Your Professional Portfolio

## Objective
Reviewed two engineering portfolios to evaluate their effectiveness as functional artifacts. Each portfolio was analyzed based on its users, functional requirements, and potential failure modes. At least one of the portfolios reviewed was hosted on GitHub.

## Analyze
## Task A - Portfolio Analysis
I compared two portfolios. The first one of from GitHub, and the second one is a interactable PDF style portfolio.

## Portfolio 1 — Nathaniel Karau (GitHub Pages)

**Portfolio:** [Nathaniel Karau's Portfolio](https://natekarau61.github.io/Engineering-Portfolio/#home)

### A. Navigability
The portfolio organizes multiple projects under a "Projects" section that is accessible from the main page. A reader can locate individual projects through this section without navigating through multiple unrelated pages.

### B. Reproducibility
The "Box Form" project provides enough technical information to partially reproduce the work. It includes the tools used, CAD models, and engineering drawings that document the manufacturing process. However, additional technical specifications may be required to fully reproduce the project.

### C. Evidence of Reasoning
The portfolio primarily presents completed project results rather than documenting the design process. It mentions achieving "zero failures over multiple casting cycles," but provides limited information about the design decisions, testing process, or problems encountered before reaching the final result.

### D. Professional Tone
The portfolio is structured similarly to a resume and includes information relevant to an employer, including personal projects, an "About Me" section, contact information, and work experience. The writing contains no noticeable spelling errors and presents the information in a format appropriate for an engineering portfolio. 

## Portfolio 2 — Andre Pacheco (PDF)

**Portfolio:** [Andre Pacheco's Portfolio](https://pachecoandre.com.br/assets/files/andre-pacheco-eng-undergrad-portfolio.pdf)

### A. Navigability
The portfolio includes a table of contents that uses hyperlinks to direct the reader to specific sections and headings. This allows a reader to navigate between major sections without manually searching through the entire portfolio.

### B. Reproducibility
The documentation does not contain enough technical information to fully reproduce the projects without additional questions. It identifies basic tools and technologies, such as C++ and CAD models, but provides limited information about specific dimensions, design parameters, or the code used to produce the final results.

### C. Evidence of Reasoning
The portfolio primarily documents the final results of the projects rather than the engineering process used to reach them. It provides limited information about design iterations, failures, constraints, or the methods used to resolve problems.

### D. Professional Tone
The portfolio presents information about himself, personal projects, and engineering experience in a format intended for potential employers. However, it does not provide contact information, which limits an employer's ability to follow up with the author regarding potential opportunities.

## Task B - Product Analysis "Stainless Steel Scissors"
## A. Primary Function

The primary mechanical function of scissors is to convert an applied force at the handles into a cutting force at the blades. The handles rotate about the pivot, causing the blades to move relative to each other and apply opposing forces to the material. For this analysis, the material being cut is paper.

## B. Governing Model

The primary governing model for the scissors is the **law of the lever**, which is based on torque equilibrium about the pivot.


FL = FoLo


Where:

- F = force applied to the handle
- L = distance from the pivot to where the input force is applied
- Fo = cutting force produced by the blade
- Lo = distance from the pivot to where the cutting force acts

This model describes how the force applied to the handles produces a torque about the pivot, which is transferred to the blades to cut the paper. Scissors operate as two first-class levers connected at a common pivot. :contentReference[oaicite:0]{index=0}

**Assumption:** The blades and handles are treated as rigid components, and friction at the pivot is assumed to be negligible. This allows the input and output torques to be modeled using the lever equation without accounting for deformation or frictional losses.

## C. Component Geometry

### Component 1 — Left Blade and Handle

![Left blade and handle](../images/IMG_6457.jpeg)

The blade is long and tapered, with a sharpened edge extending toward the tip. The tapered geometry allows the cutting location to move along the blade as the scissors close. The handle extends a greater distance from the pivot and includes a large finger opening. This increases the distance between the applied hand force and the pivot, increasing the input moment.

### Component 2 — Right Blade and Handle

![Right blade and handle](../images/IMG_6459.jpeg)

The second blade mirrors the first and works together with it to produce a shearing action. Its tapered profile allows the two cutting edges to remain in contact as they move past each other. The handle contains a large finger opening that provides a location for applying force at a relatively large distance from the pivot.

### Component 3 — Pivot Screw

![Pivot screw](../images/IMG_6458.jpeg)

The pivot screw connects the two blade and handle assemblies while allowing them to rotate relative to each other. Its location establishes the fulcrum for both lever arms. The position of the pivot determines the distances from the applied handle force and the cutting location, directly affecting the mechanical advantage.

### Full Assembly

![Full scissors assembly](../images/IMG_6456.jpeg)

The overall geometry combines the two lever arms and the pivot into a mechanism that converts the force applied at the handles into opposing forces at the blades.

## D. Patent Research

**Patent:** [US7458160B2 — Scissors](https://patents.google.com/patent/US7458160B2/en)

**Inventors:** Juan Carlos Escobar, Justin John Adelff, and Dino Anthony Mariano

### i. Alternative Solutions

Two alternative devices that perform the same primary function of cutting paper are:

1. **Paper cutter/guillotine**  uses a hinged blade to shear paper.
2. **Utility knife**  uses a single sharpened blade to cut through paper.

### ii. Design Decision

One noticeable design decision is the shape and size of the scissors' handle. The handle has a large opening that provides enough space for users with larger hands while also allowing the scissors to be operated comfortably by either left or right-handed users. This design prioritizes usability and accommodates a wider range of users while maintaining the lever arm needed to apply force to the blades.
## Decide
## Homepage Identity
The homepage is designed to serve as an organized record of my engineering work and development. It provides students, professors, and potential employers with access to my previous assignments and projects while allowing them to understand how my engineering skills have developed over time. The content is organized so that visitors can locate individual pieces of work and review the documentation behind each project. The portfolio emphasizes detailed documentation and problem-solving to show not only the completed work but also the engineering process behind it. The homepage is intended to give visitors an immediate understanding of the purpose and organization of the portfolio while demonstrating my passion for engineering through the work documented throughout it.
### One Intentional Customization

I changed the assignment labels in the navigation from generic labels such as "A1," "A2," "A3," and so on to descriptive names that identify the content of each assignment. This change better satisfies the **navigability requirement** because students, professors, and employers can identify the purpose of an assignment without already knowing the course assignment numbering. The template's default labels did not provide enough information about the content of each page, requiring visitors to open individual assignments to determine what they contained. Descriptive labels allow visitors to locate specific work more efficiently and make the portfolio easier to navigate.

# My Documentation Standard

**Every assignment entry will contain accurate technical information, evidence of the design and problem-solving process, and enough documentation for a student, professor, or employer to understand and evaluate the work without needing additional clarification.**


## Communicate

This section was answered in the **About Me** section which helps briefly introduces me and as to why I am an engineer
