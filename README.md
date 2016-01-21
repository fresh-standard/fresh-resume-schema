FRESCA
======
*The FRESH Résumé & Employment Schema*

The [FRESH][fresh] résumé schema is an open source, standards-friendly,
JSON/YAML-driven format for résumé / CVs and other employment artifacts.

- [**View the official FRESH schema document.**][schema]
- [**View a sample FRESH resume.**][exemplar]

FRESH is supported as a native format by both [FluentCV Desktop][fluentcv] and
[Command Line][npm] and can be trivially converted to and from
[JSON Resume][jrs].

## What It Does

FRESCA establishes an optimized, human-readable, computer-friendly
representation for your résumé and career data based on JSON or equivalent
YAML...

```js
// Pared-down FRESH/FRESCA resume representation (JSON)
{
  "name": "Jane Doe",
  "info": { /* Basic info */ },
  "contact": { /* Contact information */ },
  "location": { /* Location / address */ },
  "meta": { /* Resume metadata */ },
  "employment": { /* Employment history */ },
  "projects": [ /* Project history */ ],
  "skills": [ /* Skills and technologies */ ],
  "education": { /* Schools, training, certifications */ },
  "affiliation": { /* Clubs, groups, and associations */ },
  "service": { /* Volunteer, military, civilian service */ },
  "disposition": { /* Disposition towards work, relocation, schedule */ },
  "writing": [ /* Writing, blogging, and publications */ ],
  "reading": [ /* Books and publication a la StackOverflow Careers */ ],
  "speaking": [ /* Writing, blogging, and publications */ ],
  "governance": [ /* Board memberships, committees, standards groups */ ],
  "recognition": [ /* Awards and commendations */ ],
  "samples": [ /* Work samples and portfolio pieces */ ],
  "social": [ /* Social networking & engagement */ ],
  "references": [ /* Candidate references */ ],
  "testimonials": [ /* Public candidate testimonials */ ],  
  "extracurricular": [ /* Interests & hobbies */ ],
  "interests": [ /* Interests & hobbies */ ],
  "languages": [ /* languages spoken */ ]
}
```

..which you can use to generate resumes and other career artifacts in specific
concrete formats (HTML, LaTeX, Markdown, PDF, etc.) as well as enable
21st-century analysis of your resume and career data...

![](http://fluentdesk.com/img/fluentcv_desktop_alpha.png)

...in a way that's not possible with traditional, 20th-century resume tools and
formats.

## Anatomy of a FRESH Resume

FRESCA resumes are:

- Text-based.
- Versionable.
- Standards-compliant.
- Human-readable/editable.
- Computer-friendly / easily parsable by tools.
- Built from JSON or equivalent YAML.
- Used to generate specific formats like HTML, PDF, or LaTeX.
- Free from proprietary structures or site- and/or tool-specific lock-in.

## License

The FRESH resume schema is licensed under MIT. Go crazy.

[fresh]: https://github.com/fluentdesk/FRESH
[schema]: schema/fresh-resume-schema.json
[cli]: https://www.npmjs.com/package/fluentcv
[fluentcv]: http://fluentdesk.com/fluentcv
[jrs]: http://jsonresume.org
[exemplar]: https://github.com/fluentdesk/jane-q-fullstacker/blob/master/resume/jane-resume.json
[npm]: https://www.npmjs.com/package/fluentcv
