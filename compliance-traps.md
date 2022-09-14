# Compliance Traps of TDOSCA-TC11-PLAINHW

* This app uses internal classes licensed under different licenses:
  - Default License: M.I.T (see LICENSE in the top directory)
  - Greeter.java :- A.p.a.c.h.e-2.0 (see file header)
  - GreeterTest.java :- A.p.a.c.h.e-2.0 (see file header)
  - Tipster.java :- (see file header)
  - TipsterTest.java :- (see file header)

* The file LICENSE contains the text of the MIT license but does not explicitly declare to be the MIT license

* Additionally the software depends on the external 3rd party components
  * apache-log4j:
    - repository: https://logging.apache.org/log4j/2.x/download.html
    - license: Apache-2.0
    - NOTICE.txt: yes
  * joda-time
    - repository: https://github.com/JodaOrg/joda-time/releases
    - license: Apache-2.0
    - NOTICE.txt: yes
  - The graddle wrapper elements are licensed under the the Apache-v2 license

* Finally the software contains the gradle wrapper script, created by 'gradle wrapper' and the gradle-wrapper.jar  both licensed under the Apache-v2 license (= LICENSE.gradle) => A tool which automatically generates the sufficient compliance artifacts must/should create
  - the artifacts for the repository (= including the gradle artifacts)
  - the artifacts for the tdosca-tc04.jar file (= excluding the gradle artifacts)


  **Why do we write the license names in a 'dotted' version in this file?**

  *In this text (and in some source files) we describe the used licenses. But these descriptions shall not be taken as licensing statements by the scanning tools.*
