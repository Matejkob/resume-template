# Resume Template

A clean, customizable LaTeX resume template designed for professionals across various industries. This template allows for easy customization to suit your personal style and career goals.
![Example](https://github.com/user-attachments/assets/f279af01-1e70-445c-9e38-1641dadcfe44)

## Usage

1. **Overleaf (Recommended)**:
   - Go to [Overleaf](https://www.overleaf.com/) and sign in or create a free account if you don't have one.
   - Click on `New Project` and choose `Blank Project`.
   - Name your project, then upload both `resume_content.tex` and `resume_main.tex` files into the project.
   - Open `resume_main.tex` in the Overleaf editor.
   - Click on the `Recompile` button to generate your PDF resume.

2. **Local Setup**:
   - Install a LaTeX distribution: [TeX Live](https://www.tug.org/texlive/) for Linux/Windows, [MacTeX](https://www.tug.org/mactex/) for macOS.
   - Clone this repository to your local machine.
   - Open `resume_main.tex` in your preferred LaTeX editor.
   - Compile the document to generate your PDF resume.

## Customization

### Personal Information

Edit the following commands in `resume_content.tex` to update your personal details:

```latex
\name{Your Name}
\email{your.email@example.com}
\phone{+1234567890}
\linkedin{linkedin.com/in/yourprofile}
\github{github.com/yourusername}
```

### Summary

Modify the `\summary` command to reflect your professional summary:

```latex
\newcommand{\summary}{Your professional summary goes here. Highlight your key skills and career objectives.}
```

### Work Experience

Update the `\workexperience` command with your work history. Use the following format for each job:

```latex
\textbf{Job Title} | Company Name \hfill Start Date - End Date

\begin{itemize}
    \item Achievement or responsibility
    \item Another achievement or responsibility
\end{itemize}
```

### Education

Edit the education section using these commands:

```latex
\newcommand{\university}{University Name}
\newcommand{\universitylocation}{City, Country}
\newcommand{\educationdates}{Start Year - End Year}
\newcommand{\degree}{Your Degree}
\newcommand{\educationdescription}{Brief description of your studies, achievements, or relevant coursework.}
```

### Projects

Update the `\projects` command to showcase your projects. Use a similar format to the work experience section.

### Skills

Modify the `\skills` command to list your skills. Use the `\skillBullet` command to separate skills:

```latex
\newcommand{\skills}{
\textbf{Category:} Skill 1 \skillBullet Skill 2 \skillBullet Skill 3
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
