\# Moqui Tutorial Component



This repository contains a custom Moqui Framework component created while

following the official \*\*Moqui Quick Tutorial\*\*.



The goal of this component is to understand how Moqui structures applications

using declarative XML artifacts rather than imperative code.



---



\## What this component demonstrates



\- \*\*Screens\*\*

&nbsp; - Root screen and subscreens

&nbsp; - Screen hierarchy via directory structure

&nbsp; - Transitions and screen-to-service flow



\- \*\*Entities\*\*

&nbsp; - Entity definition using XML

&nbsp; - Demo data loading via entity-facade-xml

&nbsp; - Entity resolution and usage in screens and services



\- \*\*Services\*\*

&nbsp; - Implicit entity-auto services (`create#Entity`)

&nbsp; - Explicit entity-auto services defined in XML

&nbsp; - Inline services with XML actions

&nbsp; - Service resolution via directory-based naming



\- \*\*Authorization\*\*

&nbsp; - ArtifactGroup

&nbsp; - ArtifactGroupMember

&nbsp; - ArtifactAuthz



---



This is a learning-focused repository, not a production application.



---



\## Structure



tutorial/

├── MoquiConf.xml

├── data/

├── entity/

├── screen/

├── service/

└── script/





Each directory corresponds to a Moqui artifact type and follows Moqui’s

convention-over-configuration approach.



---



\## Notes



\- This repository contains \*\*only the custom component\*\*, not the full Moqui framework.

\- It is intended to be mounted inside a Moqui runtime under `runtime/component/`.

