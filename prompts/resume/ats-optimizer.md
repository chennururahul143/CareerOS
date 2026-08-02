# ATS Resume Optimization Prompt

## Purpose

Analyze a resume against a target job description and optimize it for both Applicant Tracking Systems (ATS) and human recruiters while preserving factual accuracy.

---

## Input

- Resume
- Target Job Description

---

## Expected Output

- ATS Match Score
- Recruiter Match Score
- Technical Match Score
- Missing Keywords
- Missing Skills
- Rewritten Resume
- Prioritized Improvement Plan

---

## Prompt

```text
Act as a Senior Technical Recruiter, ATS parser, Hiring Manager, Resume Writer, and AI Engineering Career Coach.

Review my resume against the provided job description.

Step 1 – ATS Analysis

Extract every:

- Technical skill
- Programming language
- Framework
- Database
- Cloud technology
- AI/ML technology
- DevOps tool
- Qualification
- Responsibility
- Preferred requirement

Group them logically.

---

Step 2 – Resume Match

Compare my resume against the extracted requirements.

Return:

- ATS Match Score (/100)
- Technical Match Score (/100)
- Experience Match Score (/100)
- Recruiter Match Score (/100)

Identify:

- Missing keywords
- Missing technical skills
- Weak bullet points
- Missing measurable impact
- Redundant content

---

Step 3 – Resume Rewrite

Rewrite every section while keeping all information truthful.

Optimize:

- Professional Summary
- Experience
- Projects
- Skills
- Certifications

Apply Google's XYZ Formula.

Every bullet should:

- Begin with a strong action verb
- Include measurable impact
- Be ATS friendly
- Read naturally
- Avoid keyword stuffing

---

Step 4 – AI Engineer Positioning

Evaluate whether the resume positions me well for:

- AI Engineer
- Applied AI Engineer
- Machine Learning Engineer
- Software Engineer

Recommend improvements.

---

Step 5 – Keyword Optimization

Identify:

- Missing recruiter keywords
- Missing ATS keywords
- Overused keywords
- Better keyword placement

---

Step 6 – Final Review

Return:

- Overall Resume Score (/10)
- ATS Score (/10)
- Recruiter Score (/10)
- AI Engineer Score (/10)
- Software Engineer Score (/10)

Finally produce:

- A rewritten resume
- A prioritized improvement roadmap
- A final submission checklist
```

---

## Best Practices

- Always use the latest resume.
- Tailor the resume for every application.
- Quantify achievements where possible.
- Keep the resume truthful.

---

## Limitations

- Depends on the quality of the supplied resume and job description.
- Cannot infer experience that is not present.

---

## Related Playbooks

- Resume Playbook
- LinkedIn Playbook
- Job Search Playbook
