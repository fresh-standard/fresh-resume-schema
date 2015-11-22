FRESCA
======
*The FRESH Resume & Employment Schema*

The [FRESH][fresh] resume schema, aka FRESCA, is an open source, standards-friendly,
JSON/YAML-driven standard for resumes / CVs and other employment artifacts.
It establishes an optimized, human-readable, computer-friendly representation
for resume and career data based on JSON or equivalent YAML.

```js
// Pared-down FRESH/FRESCA resume representation (JSON)
{
  "name": "Jane Doe",
  "info": { /* Basic info */ },
  "contact": { /* Contact information */ },
  "location": { /* Location / address */ },
  "employment": { /* Employment history */ },
  "skills": [ /* Skills and technologies */ ],
  "education": { /* Schools, training, certifications */ },
  "service": { /* Volunteer, military, civilian service */ },
  "writing": { /* Writing, blogging, and publications */ },
  "recognition": { /* Awards and commendations */ },
  "samples": [ /* Work samples and portfolio pieces */ ],
  "social": [ /* Social networking & engagement */ ],
  "references": [ /* Candidate references */ ],
  "testimonials": [ /* Public candidate testimonials */ ],  
  "interests": [ /* Interests & hobbies */ ],
  "meta": { /* Resume metadata */ }
}
```

FRESCA is compatible with but does not require [FRESH][fresh]. It is an
abstract, standalone representational schema for employment artifacts. FRESCA is
used by [FluentCV][fluentcv], [FCV:CLI][cli], and can be converted to and from
[JSON Resume][jrs] format without losing data.

## Contents

The official FRESH reference schema document for standard resumes:

- [**/schema/fresh-resume-schema.json**][schema]

Sample exemplar resumes based on the above schema, in JSON and YAML formats:

- [**/exemplar/**][exemplar]

Other files:

- `README.md`: This file.
- `package.json`: For installing the FRESH schema as an NPM dependency.
- `bower.json`: For installing FRESH schema as a Bower dependency.
- `LICENSE.md`: MIT license.

## License

The FRESH resume schema is licensed under MIT.

[fresh]: https://github.com/fluentdesk/FRESH
[schema]: schema/fresh-resume-schema.json
[cli]: https://www.npmjs.com/package/fluentcv
[fluentcv]: http://fluentdesk.com/fluentcv
[jrs]: http://jsonresume.org
[exemplar]: exemplar
