# Veronika Dementey

**Telegram:** [t.me/@NikaDementey](https://t.me/@NikaDementey)
**LinkedIn:** [linkedin.com/in/veronika-dementey-26150388](https://www.linkedin.com/in/veronika-dementey-26150388)

---

## About Me

My main goal is to stay up to date with current trends in programming and not lose my grip while I am currently unemployed. I previously worked as a full-stack developer with over three years of experience across various technologies—primarily C# on the backend, and Ext.NET, Vue.js 2, and Angular on the frontend.

After losing my job, I made the decision to switch into frontend development and dig deep into the areas where I felt my knowledge was lacking. I am now focused on filling the gaps in my understanding of modern HTML, CSS, and JavaScript/TypeScript.

My strengths include being communicative, attentive to details, creative, and I bring a user-focused mindset along with strong collaboration skills. I look forward to working on interesting projects and am open to participating in collaborations as a volunteer.

---

## Skills

### Programming Languages

C#, JavaScript, TypeScript, HTML5, CSS3, Python, SQL

### Frontend Frameworks & Libraries

React, Vue.js 2, Angular, Ext.NET, Razor Views (ASP.NET MVC)

### Backend Frameworks

ASP.NET MVC, .NET

### Databases

MSSQL, Firebase

### Version Control

Git, Git Bash

### Methodologies & Approaches

User-focused development, Collaborative teamwork, Detail-oriented problem-solving, Design Patterns, SOLID Principles, YAGNI, TDD (Test-Driven Development), DDD (Domain-Driven Design)

### Development Tools

Visual Studio, Visual Studio Code, Postman, SSMS (SQL Server Management Studio), KDiff, Figma, Zeplin, Photoshop, Trello, Todoist, Evernote, Google Calendar

---

## Code Examples

```javascript
const createArrayOfPagesBySelectedPattern = () => {
  for (let i = 1; i <= Math.min(boundaries, totalPages); i++) {
    pageNumbers.push(i);
  }
  const shouldShowLeftEllipsis = page - siblings > boundaries + 1;
  if (shouldShowLeftEllipsis) {
    pageNumbers.push(-1);
  }
  const start = Math.max(boundaries + 1, page - siblings);
  const end = Math.min(totalPages - boundaries, page + siblings);
  for (let i = start; i <= end; i++) {
    if (i > boundaries && i <= totalPages - boundaries) {
      pageNumbers.push(i);
    }
  }
  const shouldShowRightEllipsis = page + siblings < totalPages - boundaries;
  if (shouldShowRightEllipsis) {
    pageNumbers.push(-2);
  }
  for (
    let i = Math.max(totalPages - boundaries + 1, boundaries + 1);
    i <= totalPages;
    i++
  ) {
    pageNumbers.push(i);
  }
};
```

---

## Work Experience

Software Developer

### Alverden Systems · Full-time

Oct 2018 - Jul 2020 · 1 yr 10 mos
Минск · Hybrid
Developing front-end, making html layouts, implementing new designs, supporting c# features.

### Scand

Jun 2017 - Aug 2018 · 1 yr 3 mos
Support and customization of different projects

### System Technologies

Nov 2014 - May 2017 · 2 yrs 7 mos
Supporting and developing projects on Ext.net(ASP.net, MVC, C#), creating reports(SSRS), working on integration of databases(SSIS), support on analysis services(SSAS) and Data Warehouse.

---

## Education

### Belarusian State University of Informatics and Radioelectronics

Bachelor's degree, Computer Science
2009 – 2014

### RS School React Course

The Rolling Scopes School
Issued Sep 2025

---

## English Language

EF SET English Certificate 60/100 (B2 Upper Intermediate)
Issued Dec 2025
