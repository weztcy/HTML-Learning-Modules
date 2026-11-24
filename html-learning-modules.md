# Portfolio Project Data — HTML Learning Modules

- **Category:** `code-learning` (`Code Learning`)
- **Accent Color:** `orange`
- **Target Assets Folder:** `public/images/projects/html_learning_modules/`
- **Required Local Images:** `banner.webp` ONLY

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "html-learning-modules",
  "code": "PRO-47 // CL-03",
  "title": "HTML Learning Modules",
  "category": "code-learning",
  "categoryLabel": "Code Learning",
  "year": "2025",
  "status": "Completed",
  "accentColor": "orange",
  "repoUrl": "https://github.com/weztcy/HTML-Learning-Modules",
  "license": "MIT License",
  "banner": "/images/projects/html_learning_modules/banner.webp",
  "summary": "A structured 18-module HTML5 curriculum with 300 isolated lessons, study guides, and verified browser renders from fundamentals to modern web APIs.",
  "codeLearningDescription": "An incremental 18-module HTML5 curriculum spanning 300 self-contained submodules, per-module study guides, and 300 rendered PNG outputs. It progresses from DOCTYPE anatomy, forms, and semantics to WAI-ARIA accessibility, SVG/Canvas, internationalization, and 10 practical web projects.",
  "architectureSummary": "18 Sequential Module Directories -> 300 Isolated HTML5 Submodules + Module Study Guides -> Browser Rendering & 300 PNG Output Captures",
  "techStack": [
    "HTML",
    "CSS",
    "JavaScript",
    "SVG",
    "Canvas API",
    "WebVTT",
    "WAI-ARIA",
    "Web Components",
    "VS Code"
  ],
  "telemetryMatrix": {
    "projectType": "Structured HTML5 Code Curriculum",
    "targetPlatform": "Modern Web Browsers & Static Hosting",
    "primaryDomain": "Frontend Markup & Web Accessibility",
    "architecturePipeline": "18 Modules -> 300 HTML Files -> 300 PNGs",
    "testingAndAudit": "Verified",
    "projectStatus": "Completed",
    "projectYear": "2025"
  },
  "codeLearningProjectInfo": {
    "learningCategory": "Web Markup & Frontend Standards Curriculum",
    "difficultyLevel": "Beginner to Advanced",
    "programmingLanguages": "HTML, CSS & JavaScript"
  },
  "codeLearningObjectives": [
    {
      "title": "HTML Document Anatomy & Text Semantics",
      "description": "Construct valid HTML5 skeletons with proper DOCTYPE declarations, global attributes, heading hierarchies, lists, and semantic text formatting.",
      "competencyCode": "COMP_01"
    },
    {
      "title": "Interactive Forms & Native Validation",
      "description": "Design accessible data-entry workflows using typed inputs, fieldset groupings, datalist suggestions, and browser-native validation attributes.",
      "competencyCode": "COMP_02"
    },
    {
      "title": "Semantic Landmarks, Metadata & Media",
      "description": "Architect crawlable, SEO-ready documents with Open Graph metadata, landmark tags, responsive picture elements, WebVTT tracks, and sandboxed iframes.",
      "competencyCode": "COMP_03"
    },
    {
      "title": "WAI-ARIA Accessibility & Internationalization",
      "description": "Build inclusive web interfaces using ARIA roles, live regions, keyboard tabindex control, RTL/BiDi isolation, Ruby annotations, and Microdata.",
      "competencyCode": "COMP_04"
    },
    {
      "title": "Modern Browser Features & Quality Audits",
      "description": "Implement Popover APIs, inert states, dialogs, templates, Custom Elements, and W3C quality audits before delivering full-page HTML projects.",
      "competencyCode": "COMP_05"
    }
  ],
  "codeLearningPrerequisites": [
    {
      "category": "Knowledge Baseline",
      "items": [
        "Basic computer file navigation and folder management",
        "No prior HTML, CSS, or JavaScript coding experience required"
      ],
      "description": "Designed as a zero-prerequisite entry path that introduces fundamental markup syntax in Module 01 before scaling toward advanced web standards."
    },
    {
      "category": "Development Tooling",
      "items": [
        "Modern web browser (Google Chrome, Mozilla Firefox, or Microsoft Edge)",
        "Visual Studio Code with optional Live Server extension for local HTTP testing"
      ],
      "description": "All 300 submodules run directly in the browser without package managers, compilers, or external runtime installations."
    }
  ],
  "codeLearningCurriculumStructure": {
    "summary": "The curriculum scales linearly across 18 modules and 300 isolated HTML lessons, moving from core document syntax, lists, and forms to semantic architecture, WAI-ARIA accessibility, vector/canvas graphics, modern HTML elements, and 10 real-world capstone builds.",
    "totalEstimatedHours": "75 Hours",
    "phases": [
      {
        "phaseNumber": "01",
        "phaseTitle": "Core Markup & Navigation Foundations",
        "difficulty": "Beginner",
        "moduleRange": "Modules 01 - 04",
        "topics": [
          "DOCTYPE, tags, attributes & DOM nesting",
          "Headings, text formatting & code blocks",
          "Hyperlinks, URLs, anchors & nav menus",
          "Ordered, unordered & description lists"
        ]
      },
      {
        "phaseNumber": "02",
        "phaseTitle": "Visual Media, Tables & Form Controls",
        "difficulty": "Beginner",
        "moduleRange": "Modules 05 - 08",
        "topics": [
          "Responsive images, srcset, picture & image maps",
          "Semantic data tables with scope & headers",
          "GET/POST forms & 20+ native input types",
          "Fieldsets, datalist, meter, progress & validation"
        ]
      },
      {
        "phaseNumber": "03",
        "phaseTitle": "Semantic Architecture, SEO & Embedded Media",
        "difficulty": "Intermediate",
        "moduleRange": "Modules 09 - 12",
        "topics": [
          "HTML5 landmarks, details, dialog & search",
          "Head metadata, defer/async & Open Graph SEO",
          "Audio, video, poster & WebVTT caption tracks",
          "Sandboxed iframes, embed, object & PDF/Maps"
        ]
      },
      {
        "phaseNumber": "04",
        "phaseTitle": "Accessibility, Graphics & Global Standards",
        "difficulty": "Intermediate",
        "moduleRange": "Modules 13 - 15",
        "topics": [
          "WAI-ARIA states, live regions & keyboard nav",
          "Inline SVG shapes, viewBox & Canvas 2D API",
          "RTL directionality, bdi/bdo, ruby & Microdata"
        ]
      },
      {
        "phaseNumber": "05",
        "phaseTitle": "Modern HTML APIs, Audits & Applied Capstones",
        "difficulty": "Advanced",
        "moduleRange": "Modules 16 - 18",
        "topics": [
          "Popover API, inert, template, slot & Custom Elements",
          "Nesting, ID, a11y, performance & security audits",
          "10 end-to-end semantic & multi-page web projects"
        ]
      }
    ]
  },
  "codeLearningModules": [
    {
      "id": "mod-01",
      "moduleNumber": "01",
      "title": "HTML Introduction & Document Structure",
      "description": "Introduces the HTML5 skeleton, DOCTYPE, start/end tags, attributes, nesting rules, indentation, comments, entities, void elements, and global attributes.",
      "submoduleCount": 15,
      "difficulty": "Beginner",
      "keyTopics": ["DOCTYPE Declaration", "Element Nesting", "HTML Entities", "Void Elements", "Global Attributes"],
      "sourceFilesCount": 15,
      "estimatedHours": "3 Hours"
    },
    {
      "id": "mod-02",
      "moduleNumber": "02",
      "title": "Headings, Text & Formatting",
      "description": "Covers structural headings h1 through h6, paragraphs, line breaks, semantic emphasis, annotations, citations, blockquotes, and preformatted code.",
      "submoduleCount": 20,
      "difficulty": "Beginner",
      "keyTopics": ["Heading Hierarchy", "Semantic Emphasis", "Citations & Quotes", "Preformatted Code"],
      "sourceFilesCount": 20,
      "estimatedHours": "4 Hours"
    },
    {
      "id": "mod-03",
      "moduleNumber": "03",
      "title": "Hyperlinks & Navigation",
      "description": "Explores anchor tags, absolute and relative URLs, target/rel security attributes, mailto/tel protocols, downloads, breadcrumbs, and nav landmarks.",
      "submoduleCount": 15,
      "difficulty": "Beginner",
      "keyTopics": ["Absolute vs Relative URLs", "Link Security (rel)", "Anchor Navigation", "Breadcrumb & Nav"],
      "sourceFilesCount": 15,
      "estimatedHours": "3 Hours"
    },
    {
      "id": "mod-04",
      "moduleNumber": "04",
      "title": "Lists & Content Grouping",
      "description": "Teaches unordered, ordered, nested, and reversed lists alongside definition lists (dl/dt/dd) and list-driven navigation structures.",
      "submoduleCount": 12,
      "difficulty": "Beginner",
      "keyTopics": ["Ordered & Unordered Lists", "List Ordering Attributes", "Description Lists", "Navigation Lists"],
      "sourceFilesCount": 12,
      "estimatedHours": "2 Hours"
    },
    {
      "id": "mod-05",
      "moduleNumber": "05",
      "title": "Images & Visual Media",
      "description": "Demonstrates image embedding, descriptive alt text, figure captions, responsive picture/srcset/sizes switching, lazy loading, and interactive image maps.",
      "submoduleCount": 18,
      "difficulty": "Beginner",
      "keyTopics": ["Figure & Figcaption", "Responsive Picture & Srcset", "Lazy Loading & Decoding", "Image Maps"],
      "sourceFilesCount": 18,
      "estimatedHours": "4 Hours"
    },
    {
      "id": "mod-06",
      "moduleNumber": "06",
      "title": "HTML Tables",
      "description": "Builds structured tabular layouts using thead, tbody, tfoot, captions, merged cells (colspan/rowspan), colgroup styling, and accessible scope/headers.",
      "submoduleCount": 15,
      "difficulty": "Beginner",
      "keyTopics": ["Table Sections", "Colspan & Rowspan", "Colgroup & Col", "Accessible Scope & Headers"],
      "sourceFilesCount": 15,
      "estimatedHours": "3 Hours"
    },
    {
      "id": "mod-07",
      "moduleNumber": "07",
      "title": "Basic Forms & Inputs",
      "description": "Provides comprehensive coverage of GET/POST form submission and 20+ specialized HTML5 input controls, textareas, buttons, and grouped select menus.",
      "submoduleCount": 30,
      "difficulty": "Beginner",
      "keyTopics": ["GET & POST Methods", "HTML5 Input Types", "Checkboxes & Radios", "Select & Optgroup"],
      "sourceFilesCount": 30,
      "estimatedHours": "6 Hours"
    },
    {
      "id": "mod-08",
      "moduleNumber": "08",
      "title": "Advanced Forms & Validation",
      "description": "Covers accessible form labeling, fieldsets, datalist autocomplete, output/meter/progress indicators, regex pattern constraints, and native browser validation.",
      "submoduleCount": 20,
      "difficulty": "Beginner",
      "keyTopics": ["Fieldset & Legend", "Datalist & Output", "Meter & Progress", "Regex & Constraint Validation"],
      "sourceFilesCount": 20,
      "estimatedHours": "5 Hours"
    },
    {
      "id": "mod-09",
      "moduleNumber": "09",
      "title": "Semantic HTML",
      "description": "Contrasts semantic elements against generic divs and demonstrates header, footer, main, section, article, aside, details, dialog, search, and full page layouts.",
      "submoduleCount": 20,
      "difficulty": "Intermediate",
      "keyTopics": ["Page Landmarks", "Time & Data Tags", "Details & Dialog", "Semantic Page Blueprints"],
      "sourceFilesCount": 20,
      "estimatedHours": "5 Hours"
    },
    {
      "id": "mod-10",
      "moduleNumber": "10",
      "title": "Head, Metadata & SEO",
      "description": "Details head configuration, viewport scaling, SEO meta tags, favicons, external CSS/JS linking, defer/async script loading, canonical URLs, and Open Graph.",
      "submoduleCount": 15,
      "difficulty": "Intermediate",
      "keyTopics": ["SEO Meta Tags", "Defer & Async Scripts", "Canonical Links", "Open Graph Metadata"],
      "sourceFilesCount": 15,
      "estimatedHours": "4 Hours"
    },
    {
      "id": "mod-11",
      "moduleNumber": "11",
      "title": "Audio, Video & Multimedia",
      "description": "Implements native audio and video players with multi-format sources, fallback content, poster frames, WebVTT subtitle tracks, preload hints, and accessibility.",
      "submoduleCount": 15,
      "difficulty": "Intermediate",
      "keyTopics": ["Audio & Video Controls", "Multi-Source Fallbacks", "WebVTT Subtitles", "Multimedia Accessibility"],
      "sourceFilesCount": 15,
      "estimatedHours": "4 Hours"
    },
    {
      "id": "mod-12",
      "moduleNumber": "12",
      "title": "Iframe & Embedded Content",
      "description": "Teaches secure third-party and local embedding with iframe sandbox policies, referrerpolicy, lazy loading, embed/object tags, PDF/SVG embeds, and responsive containers.",
      "submoduleCount": 15,
      "difficulty": "Intermediate",
      "keyTopics": ["Iframe Sandbox Security", "Referrer Policy", "Embed & Object Elements", "Responsive Iframes"],
      "sourceFilesCount": 15,
      "estimatedHours": "4 Hours"
    },
    {
      "id": "mod-13",
      "moduleNumber": "13",
      "title": "HTML Accessibility",
      "description": "Deep-dives into WCAG-aligned markup covering document landmarks, keyboard navigation, tabindex management, ARIA labels, live regions, expanded states, and audits.",
      "submoduleCount": 20,
      "difficulty": "Intermediate",
      "keyTopics": ["Keyboard & Tabindex", "ARIA Labels & Descriptions", "ARIA Live & Controls", "Accessibility Auditing"],
      "sourceFilesCount": 20,
      "estimatedHours": "6 Hours"
    },
    {
      "id": "mod-14",
      "moduleNumber": "14",
      "title": "SVG, Canvas & Graphics",
      "description": "Covers inline vector graphics (rect, circle, ellipse, line, polygon, polyline, path, viewBox), SVG accessibility, 2D raster Canvas scripting, and rendering trade-offs.",
      "submoduleCount": 15,
      "difficulty": "Intermediate",
      "keyTopics": ["Inline SVG Primitives", "SVG Path & ViewBox", "Canvas 2D Context", "SVG vs Canvas"],
      "sourceFilesCount": 15,
      "estimatedHours": "4 Hours"
    },
    {
      "id": "mod-15",
      "moduleNumber": "15",
      "title": "Internationalization & Semantic Metadata",
      "description": "Explains multi-language markup with lang, dir, RTL layouts, Unicode handling, bdi/bdo overrides, Ruby phonetic annotations, and Schema.org Microdata.",
      "submoduleCount": 15,
      "difficulty": "Intermediate",
      "keyTopics": ["Lang & RTL Direction", "BiDi Isolation (bdi/bdo)", "Ruby Annotations", "HTML5 Microdata"],
      "sourceFilesCount": 15,
      "estimatedHours": "4 Hours"
    },
    {
      "id": "mod-16",
      "moduleNumber": "16",
      "title": "Modern HTML Elements & Attributes",
      "description": "Demonstrates modern browser specifications including data-* attributes, inert, inputmode, enterkeyhint, Popover API, template/slot, Custom Elements, and dialog forms.",
      "submoduleCount": 15,
      "difficulty": "Advanced",
      "keyTopics": ["Popover API", "Inert & Inputmode", "Template & Slot", "Custom Elements & Dialog"],
      "sourceFilesCount": 15,
      "estimatedHours": "5 Hours"
    },
    {
      "id": "mod-17",
      "moduleNumber": "17",
      "title": "Validation, Performance & Quality",
      "description": "Reviews structural HTML validation, duplicate ID checks, semantic/link/image/form audits, resource loading optimization, security attributes, and clean-code standards.",
      "submoduleCount": 15,
      "difficulty": "Advanced",
      "keyTopics": ["DOM & ID Validation", "Accessibility & SEO Audits", "Resource Loading", "Security Attributes"],
      "sourceFilesCount": 15,
      "estimatedHours": "4 Hours"
    },
    {
      "id": "mod-18",
      "moduleNumber": "18",
      "title": "Practical HTML Projects",
      "description": "Applies the full curriculum across 10 realistic HTML builds ranging from personal profiles and resumes to product catalogs, survey forms, and a multi-page website.",
      "submoduleCount": 10,
      "difficulty": "Advanced",
      "keyTopics": ["Editorial & Portal Layouts", "E-Commerce Catalogs", "Validation Forms", "Multi-Page Architecture"],
      "sourceFilesCount": 10,
      "estimatedHours": "5 Hours"
    }
  ],
  "codeLearningPracticalProjects": [
    {
      "title": "Personal Profile, Portfolio & Formal Resume Suite",
      "description": "Three foundational identity projects (291-293) integrating SVG avatars, skill badge lists, semantic article portfolio cards, and formal CV timelines using time elements.",
      "highlights": [
        "Semantic header, article grid, and experience timeline layout",
        "Inline SVG avatar rendering and structured skill tags",
        "Clean print-ready CV hierarchy with verified PNG outputs"
      ],
      "coreScope": "Identity & Career Showcase Layouts",
      "trackTag": "Capstone Lab 01",
      "tier": "Core",
      "difficulty": "Intermediate",
      "estimatedTime": "1.5 Hours",
      "architecturalConstraints": [
        "Pure semantic HTML5 with embedded CSS styling",
        "Zero external frameworks or build tools"
      ]
    },
    {
      "title": "Editorial Blog Article & News Portal Architecture",
      "description": "Media publishing builds (294-295) combining article metadata, time elements, styled blockquotes, breaking-news banners, and multi-story headline hierarchies.",
      "highlights": [
        "Journalistic article structure with blockquote citations",
        "Layered news portal separating lead headlines and secondary stories",
        "Verified responsive typography and reading flow"
      ],
      "coreScope": "Digital Publishing & Content Hierarchy",
      "trackTag": "Capstone Lab 02",
      "tier": "Core",
      "difficulty": "Intermediate",
      "estimatedTime": "1 Hour",
      "architecturalConstraints": [
        "Strict heading hierarchy without skipped levels",
        "Semantic separation of primary and secondary articles"
      ]
    },
    {
      "title": "E-Commerce Catalog, Registration & Survey Forms",
      "description": "Interactive commercial and data-collection builds (296-298) featuring product article cards, fieldset-grouped certification forms, and multi-control NPS surveys.",
      "highlights": [
        "Product grid cards with formatted pricing and action controls",
        "Accessible form validation with required fields and consent checks",
        "Survey combining radio buttons, range sliders, and textareas"
      ],
      "coreScope": "Storefront Display & User Input Workflows",
      "trackTag": "Capstone Lab 03",
      "tier": "Advanced",
      "difficulty": "Advanced",
      "estimatedTime": "1.5 Hours",
      "architecturalConstraints": [
        "Native HTML5 constraint validation without JavaScript libraries",
        "Explicit label association and fieldset grouping"
      ]
    },
    {
      "title": "Corporate Landing Page & Multi-Page Website",
      "description": "Full-site architecture projects (299-300) pairing a corporate hero landing page with a multi-document website linked to dedicated About, Services, and Contact subpages.",
      "highlights": [
        "Navbar navigation, hero call-to-action, and 3-pillar service cards",
        "Cross-linked multi-document routing into pages/about, services, and contact",
        "Zero broken relative links across root and nested page directories"
      ],
      "coreScope": "Multi-Document Web Navigation & Corporate Layout",
      "trackTag": "Capstone Lab 04",
      "tier": "Advanced",
      "difficulty": "Advanced",
      "estimatedTime": "1 Hour",
      "architecturalConstraints": [
        "Relative path integrity between root index and pages/ subfolder",
        "Consistent semantic header, nav, main, and footer across pages"
      ]
    }
  ],
  "codeLearningOutcomes": [
    {
      "pillar": "Semantic Architecture & Clean Markup",
      "skills": [
        {
          "title": "Standards-Compliant HTML5 Authoring",
          "description": "Write well-nested, lowercase, semantic HTML5 documents that pass structural nesting, duplicate-ID, metadata, and link validation checks."
        },
        {
          "title": "SEO & Multi-Page Site Structuring",
          "description": "Configure canonical metadata, Open Graph tags, and multi-document navigation hierarchies ready for search crawlers and static hosting."
        }
      ]
    },
    {
      "pillar": "Accessible & Interactive Web Interfaces",
      "skills": [
        {
          "title": "WCAG & WAI-ARIA Implementation",
          "description": "Deliver keyboard-navigable forms, tables, and interactive widgets backed by semantic landmarks, alt text, and live ARIA state attributes."
        },
        {
          "title": "Rich Media, Graphics & Modern Browser APIs",
          "description": "Combine responsive imagery, captioned video tracks, inline SVG/Canvas graphics, and native Popover/Dialog/Custom Element patterns."
        }
      ]
    }
  ],
  "codeLearningCurriculumSpecs": {
    "curriculumTrack": "Modern HTML Web Standards",
    "primaryLanguage": "HTML",
    "executionRuntime": "Modern Web Browser",
    "testVerification": "300 Rendered PNG Outputs"
  },
  "codeLearningSupplementaryResources": [
    {
      "title": "Per-Module Curriculum Guides",
      "description": "Eighteen dedicated README.md study guides detailing learning objectives, concepts, source explanations, execution steps, and expected visual outputs for every submodule.",
      "resources": [
        {
          "name": "module-01 to module-18 README.md Guides",
          "type": "Reference Guide",
          "format": "MD"
        }
      ]
    },
    {
      "title": "Media, Embed & Multi-Page Assets",
      "description": "Supporting SVG artwork, WebVTT caption tracks, sandboxed iframe targets, and linked subpage templates used across Modules 05, 11, 12, and 18.",
      "resources": [
        {
          "name": "Responsive & Poster SVG Assets (Modules 05 & 11)",
          "type": "Media Asset",
          "format": "SVG"
        },
        {
          "name": "subtitles-id.vtt Caption Track (Module 11)",
          "type": "Caption Track",
          "format": "VTT"
        },
        {
          "name": "frame_content.html & Multi-Page Subpages (Modules 12 & 18)",
          "type": "Template",
          "format": "HTML"
        }
      ]
    },
    {
      "title": "Visual Verification Captures",
      "description": "Complete set of 300 browser-rendered PNG screenshots stored in each module's output/ directory for 1:1 visual comparison against live execution.",
      "resources": [
        {
          "name": "300 Submodule Output Captures (output/*.png)",
          "type": "Execution Output",
          "format": "PNG"
        }
      ]
    }
  ]
}
```
