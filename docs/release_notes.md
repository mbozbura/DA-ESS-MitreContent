---
layout: default
title: Release Notes
---

### Release Notes:
#### Version 2.4.0
- Date: 30 Oct 2020
- Feature: New setup view to be compatible with Splunk Cloud
  - Setup.xml replaced by custom javascript.  
- Bug fix: Alert Manager 3.0.4 compatibility issues

#### Version 2.3.0
- Date: 22 Jun 2020
- Feature: Option to work with plain Splunk Enterprise (no ES requirement)
  - Added macros for flexible deployment option (default is ES app)
  - Updated views to use the macros

#### Version 2.2.0
- Date: 09 May 2020
- Bug fix: Duplication issue for Rule Finder
- Feature: Added option to display compliance matrix without default rules (user-defined/API rules only)
  - Added lookup file definitions
  - Added default rules lookup files for ES 6.1.1 and ESCU 1.0.53 out-of-the-box rules
  - Updated Lookup Generation view
- Feature: Setup.xml for API integration for continuous new rule updates (free service but requires registration)
  - Added custom search command (| getattackdetectionrules)

#### Version 2.1.0
- Date: 25 Feb 2020
- Added a new view for mapping rules to Techniques
- Updated lookup tables and some searches accordingly

#### Version 2.0.1
- Date: 12 Feb 2020
- Bug fix for appinspect validation
- Tactics overview displayed as table with updated js and css

#### Version 2.0.0
- Date: 08 Feb 2020
- Updated lookup tables to correctly define MITRE ATT&CK tactics and techniques
- Introduced a new macro to utilize technique and tactic IDs/names
- Updated dashboards to utilize new lookup table and macro
- Performance improvements
- Updated CSS and JS files
- Introduced a setup view for ease of initial lookup generation

#### Version 1.3.0
- Date: 09 Jan 2020
- Updated ATT&CK Matrix dashboard
- Added new dashboard for detailed view of triggered rules by notable assets and tactics/techniques
- Improved search performance and dependency on lookups
- Added a new lookup to match correlation rules to MITRE ATT&CK tactics/techniques

#### Version 1.2.1
- Date: 24 Oct 2019
- Bug fixes with javascript table population
- Ordering of table fields to align with MITRE ATT&CK content

#### Version 1.2.0
- Date: 24 Aug 2019
- Bug fixes & typos
- Sphinx documentation is added

#### Version 1.1.0
- Date: 06 Aug 2019
- Bug fixes & typos
- Added descriptions to dashboards
- Added improvements for initial lookup generator

#### Version 1.0.0
- Date: 25 Jul 2019
- Initial version for Splunkbase
- Test to run on 7.3.0 and ES App 5.3
