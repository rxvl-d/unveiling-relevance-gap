# unveiling-relevance-gap
Additional material for the paper "Unveiling the Relevance Gap: Search Snippets vs. Document Content in Learning Resource Search"

# Relevance Dimensions

```
rel_dimensions_desc = {
    'Motivation': {
        'label': 'D1',
        'English': "The document contain materials that are motivating or stimulating to students. i.e. The design of the website is modern and clean; the content makes an effort to engage students through interactive elements or fun activities; etc.",
        'Original-English': "The document contains materials that are motivational or stimulating (interesting, appealing, or engaging) for students",
        'Original-English-Source': "Reitsma",
        'German': "Das Dokument enthält Materialien, die für Schüler motivierend oder anregend sind. z.B. Das Design der Website ist modern und übersichtlich; der Inhalt bemüht sich, Schüler durch interaktive Elemente oder unterhaltsame Aktivitäten zu engagieren; usw.",
        'Original-German': "Das Dokument enthält Materialien, die für Schüler motivierend oder anregend (interessant, ansprechend oder fesselnd) sind"
    },
    'Concepts': {
        'label': 'D2',
        'English': "The document includes exactly the concepts, keywords, terms and definitions from the information need. i.e. For a physics topic on mechanics, it includes terms like 'force', 'mass', and 'acceleration'; for a chemistry lesson on atomic structure, it covers 'protons', 'neutrons', 'electrons'; etc.",
        'Original-English': "The document includes concepts, keywords, terms, and definitions from the standard",
        'Original-English-Source': "Reitsma",
        'German': "Das Dokument enthält genau die Konzepte, Schlüsselwörter, Begriffe und Definitionen aus dem Informationsbedarf. z.B. Für ein Physikthema über Mechanik enthält es Begriffe wie 'Kraft', 'Masse' und 'Beschleunigung'; für eine Chemielektion über Atomstruktur behandelt es 'Protonen', 'Neutronen', 'Elektronen'; usw.",
        'Original-German': "Das Dokument enthält Konzepte, Schlüsselwörter, Begriffe und Definitionen aus dem Standard"
    },
    'Background': {
        'label': 'D3',
        'English': "The document provides interesting and important background material related to the information need. i.e. For a topic on thermodynamics, it includes the history of temperature measurement; for a lesson on calculus, it covers the contributions of Newton and Leibniz; etc.",
        'Original-English': "The document provides interesting and important background material related to the standard",
        'Original-English-Source': "Reitsma",
        'German': "Das Dokument liefert interessantes und wichtiges Hintergrundmaterial zum Informationsbedarf. z.B. Für ein Thema zur Thermodynamik enthält es die Geschichte der Temperaturmessung; für eine Lektion über Differentialrechnung behandelt es die Beiträge von Newton und Leibniz; usw.",
        'Original-German': "Das Dokument liefert interessantes und wichtiges Hintergrundmaterial zum Standard"
    },
    'Grade level': {
        'label': 'D4',
        'English': "The document is appropriate for the grade level mentioned in the information need. i.e. For middle school students, it uses basic algebraic concepts; for high school students, it includes more advanced calculus and physics principles; etc.",
        'Original-English': "The grade level of this material is appropriate for this task or else I can easily adapt the materials in this document to my grade level",
        'Original-English-Source': "Reitsma",
        'German': "Das Dokument ist für das im Informationsbedarf erwähnte Klassenniveau angemessen. z.B. Für Mittelstufenschüler verwendet es grundlegende algebraische Konzepte; für Oberstufenschüler enthält es fortgeschrittenere Differential- und Integralprinzipien sowie Physikgrundlagen; usw.",
        'Original-German': "Das Niveau dieses Materials ist für diese Aufgabe angemessen, oder ich kann die Materialien in diesem Dokument leicht an mein Klassenniveau anpassen"
    },
    'Non-textuals': {
        'label': 'D5',
        'English': "The document provides relevant non-textual components pertaining to the information need. i.e. It includes diagrams; graphs; interactive simulations; video demonstrations; virtual labs; 3D models; etc.",
        'Original-English': "The grade level of this material is appropriate for this task or else I can easily adapt the materials in this document to my grade level",
        'Original-English-Source': "Reitsma",
        'German': "Das Dokument enthält relevante nicht-textuelle Komponenten, die sich auf den Informationsbedarf beziehen. z.B. Es enthält Diagramme; Grafiken; interaktive Simulationen; Video-Demonstrationen; virtuelle Labore; 3D-Modelle; usw.",
        'Original-German': "Das Niveau dieses Materials ist für diese Aufgabe angemessen, oder ich kann die Materialien in diesem Dokument leicht an mein Klassenniveau anpassen"
    },
    'Examples': {
        'label': 'D6',
        'English': "The document provides real-world examples pertaining to the information need. i.e. It includes case studies; worked problems; sample experiments; practical applications; historical anecdotes; thought experiments; etc.",
        'Original-English': "I can use the real-world examples provided in the document in class",
        'Original-English-Source': "Reitsma",
        'German': "Das Dokument liefert praxisnahe Beispiele, die sich auf den Informationsbedarf beziehen. z.B. Es enthält Fallstudien; durchgerechnete Probleme; Beispielexperimente; praktische Anwendungen; historische Anekdoten; Gedankenexperimente; usw.",
        'Original-German': "Ich kann die im Dokument bereitgestellten praxisnahen Beispiele im Unterricht verwenden"
    },
    'Hands-on': {
        'label': 'D7',
        'English': "The document provides hands-on, active engineering activities pertaining to the information need. i.e. For a physics lesson, it includes instructions for building a simple electric motor; for a chemistry unit, it provides a guide for conducting titration experiments; etc.",
        'Original-English': "I can use one or more of the hands-on, active engineering activities",
        'Original-English-Source': "Reitsma",
        'German': "Das Dokument bietet praktische, aktive Ingenieuraktivitäten, die sich auf den Informationsbedarf beziehen. z.B. Für eine Physiklektion enthält es Anweisungen zum Bau eines einfachen Elektromotors; für eine Chemieeinheit bietet es eine Anleitung zur Durchführung von Titrationsexperimenten; usw.",
        'Original-German': "Ich kann eine oder mehrere der praktischen, aktiven Ingenieuraktivitäten verwenden"
    },
    'Attachments': {
        'label': 'D8',
        'English': "The document provides attachments pertaining to the information need. i.e. It includes worksheets; lab report templates; assessment rubrics; presentation slides; data sets; code snippets; etc.",
        'Original-English': "I can use some of the attachments; e.g., score sheets, rubrics, test questions, etc.",
        'Original-English-Source': "Reitsma",
        'German': "Das Dokument enthält Anhänge, die sich auf den Informationsbedarf beziehen. z.B. Es enthält Arbeitsblätter; Vorlagen für Laborberichte; Bewertungsraster; Präsentationsfolien; Datensätze; Code-Snippets; usw.",
        'Original-German': "Ich kann einige der Anhänge verwenden, z.B. Bewertungsbögen, Rubriken, Testfragen usw."
    },
    'References': {
        'label': 'D9',
        'English': "The document provides references or internet links to relevant material elsewhere that pertain to the information need. i.e. It includes links to online textbooks; scientific journals; educational videos; interactive simulations; academic databases; subject-specific forums; etc.",
        'Original-English': "I can use references or Internet links to relevant materials elsewhere",
        'Original-English-Source': "Reitsma",
        'German': "Das Dokument enthält Referenzen oder Internetlinks zu relevantem Material an anderer Stelle, die sich auf den Informationsbedarf beziehen. z.B. Es enthält Links zu Online-Lehrbüchern; wissenschaftlichen Zeitschriften; Lehrvideos; interaktiven Simulationen; akademischen Datenbanken; fachspezifischen Foren; usw.",
        'Original-German': "Ich kann Referenzen oder Internetlinks zu relevantem Material an anderer Stelle verwenden"
    },
    'Identifies Learning Goals': {
        'label': 'D10',
        'English': "The document mentions the knowledge and skills a student is expected to acquire over the course of using it. i.e. For a math lesson, it states 'Students will be able to solve quadratic equations'; for a physics unit, it specifies 'Students will understand and apply the laws of thermodynamics'; etc.",
        'Original-English': "The document articulates the knowledge and skills a student is expected to acquire over the course of using the resource.",
        'Original-English-Source': "Wetzler",
        'German': "Das Dokument erwähnt das Wissen und die Fähigkeiten, die ein Schüler im Laufe der Nutzung erwerben soll. z.B. Für eine Mathestunde heißt es 'Schüler werden in der Lage sein, quadratische Gleichungen zu lösen'; für eine Physikeinheit wird spezifiziert 'Schüler werden die Gesetze der Thermodynamik verstehen und anwenden können'; usw.",
        'Original-German': "Das Dokument formuliert das Wissen und die Fähigkeiten, die ein Schüler im Laufe der Nutzung der Ressource erwerben soll."
    },
    'Organized for Learning Goals': {
        'label': 'D11',
        'Original-English': "The document is clearly organized so that each learning goal has a corresponding description or activity.",
        'Original-English-Source': "Wetzler",
        'English': "The document is structured according to its learning goals. i.e. Each chapter corresponds to a specific learning objective; there are clear sections for theory, examples, and practice problems; it includes concept maps linking different topics; etc.",
        'German': "Das Dokument ist entsprechend seinen Lernzielen strukturiert. z.B. Jedes Kapitel entspricht einem spezifischen Lernziel; es gibt klare Abschnitte für Theorie, Beispiele und Übungsaufgaben; es enthält Konzeptkarten, die verschiedene Themen miteinander verknüpfen; usw.",
        'Original-German': "Das Dokument ist klar organisiert, sodass jedem Lernziel eine entsprechende Beschreibung oder Aktivität zugeordnet ist."
    },
    'Prestigious Publisher': {
        'label': 'D12',
        'Original-English': "The manager or organizer of the document is respected in the field of study relevant to the resource.",
        'Original-English-Source': "Wetzler",
        'English': "The document's publisher is recognizable and is prestigious and trustworthy. i.e. It's published by a well-known university press; it's authored by a leading expert in the field; it's endorsed by reputable scientific organizations; etc.",
        'German': "Der Herausgeber des Dokuments ist erkennbar, angesehen und vertrauenswürdig. z.B. Es wird von einem bekannten Universitätsverlag veröffentlicht; es wurde von einem führenden Experten auf dem Gebiet verfasst; es wird von angesehenen wissenschaftlichen Organisationen empfohlen; usw.",
        'Original-German': "Der Verwalter oder Organisator des Dokuments wird in dem für die Ressource relevanten Studienbereich respektiert."
    },
    'Overall': {
        'label': 'D13',
        'Original-English': "Overall, I consider this document relevant for this teaching assignment.",
        'Original-English-Source': "Reitsma",
        'English': "Overall I consider this document relevant for the information need at hand. i.e. It covers all the key points of the topic; it's appropriate for the target audience; it provides useful resources for teaching or learning; it aligns with curriculum standards; etc.",
        'German': "Insgesamt betrachte ich dieses Dokument als relevant für den vorliegenden Informationsbedarf. z.B. Es deckt alle wichtigen Punkte des Themas ab; es ist für die Zielgruppe angemessen; es bietet nützliche Ressourcen zum Lehren oder Lernen; es entspricht den Lehrplanstandards; usw.",
        'Original-German': "Insgesamt betrachte ich dieses Dokument als relevant für diese Lehraufgabe."
    }
}
```
