# Specification, Design and development of a Conversation GenAI powered Dashboard and engine for Automated Grading

**Background**

![](.\/media/media/image1.png){width="4.169907042869641in"
height="3.1259339457567803in"}

-   Open-ended questions are a favoured tool among instructors for
    assessing student understanding and encouraging critical exploration
    of course material.

-   Providing graded feedback for such responses is a time-consuming
    task that can lead to overwhelmed instructors and decreased feedback
    quality.

-   Many instructors resort to simpler question formats, like
    multiple-choice questions, which provide immediate feedback but at
    the expense of personalized evaluation and insightful feedback to
    improve quality of the student experience.

-   Here, we develop a tool that uses large language models (LLMs),
    guided by instructor-defined criteria, to automated grading and
    responses to open-ended questions.

-   The tool will deliver grading and rapid personalized feedback,
    enabling teachers to evaluate students performance per a provided
    rubric as well as for students to quickly test their knowledge and
    identify areas for improvement.

-   We provide reference implementations both as a web application and
    as a Jupyter Notebook widget that can be used with instructional
    coding or math notebooks.

-   With instructor guidance, LLMs hold promise to enhance student
    learning outcomes and elevate instructional methodologies.

# 

# Approach and Discussion

![](.\/media/media/image2.png){width="7.738888888888889in"
height="3.209722222222222in"}

-   The framework will be capable of defining questions, collecting
    student responses, transmitting these responses alongside instructor
    expectations to a large language model (LLM), and generating rapid
    and personalized feedback for the students.

-   Notably, the entirety of the student-facing workflow can be accessed
    as a web application or encapsulated within a Jupyter notebook,
    facilitating real-time enhancement of students' understanding of the
    course material.

-   The tool can integrate with any application that consumes a JSON
    HTTP API, expanding its potential to a wider range of educational
    settings.

-   The tool can help small student groups or 'pods' collaboratively
    tackle assignments and projects.

-   Human Teaching Assistants, tasked with providing feedback, can
    benefit from our tool, as it can streamline grading processes,
    reducing potential for attentional errors and freeing up instructors
    to deliver more personalized guidance to students.

-   Fully automated student evaluation is challenging both from a
    technical perspective and from a human perspective, and thus this
    tool is designed not to fully automate grading, but to serve as a
    tool that strongly enhances the efficiency of the grading process
    benefiting both students and instructors.

-   The too benefits students by providing rapid and personalized
    feedback on questions.

-   The tool benefits instructors by helping them to design better
    questions and grading criteria, by providing first-pass material for
    learning assessments, and by alleviating some of the burden of
    providing individualized instruction in large classes.

-   LLMs in general, and Tools like these specifically, are not a
    replacement human instructors, but they can nonetheless fill a niche
    among education technologies.

-   While LLMs undoubtedly hold immense power and potential it is
    crucial to have an in-depth discussion about their ethical
    implications, especially in education particularly the potential
    biases that LLMs can introduce.

-   These biases could unintentionally touch on sensitive subjects or
    unintentionally overlook marginalized groups.

-   Instructors have a role to play by carefully designing their
    questions and assessment criteria.

-   Further, students should be made aware of the nature of the system
    they are interacting with and its potential to make mistakes or act
    on internalized biases.

-   On the other hand, automated systems such as this present an
    opportunity to reduce instructors' unconscious biases by evaluating
    all students' responses equally and without any explicit
    identification.

> Effort Approach and Phases

This effort uses a mixed methods approach that will be conducted in four
main phases.

-   In the first phase, all the resources related to the functional
    dashboard are reviewed in order to identify its functional and
    operational requirements.

-   In the second phase, the detailed feature statements and
    capabilities of the software are determined by both qualitative
    (interview) and quantitative (Delphi) methods.

    -   In this phase, eight people will be interviewed during the
        qualitative phase, and thematic analysis will be used to analyse
        the data.

    -   For the quantitative step, the two- round Delphi technique will
        be conducted by the purposeful selection of 21 individuals.

-   In the third phase,

    -   Deployment of the Spanda AI Software Platform will be first
        performed

    -   A custom application comprising of a conversationally enabled
        GenAI powered dashboard along with the associated model and
        generation engine is developed using Python programming language
        in an IDE

    -   The application will be deployed on a private cloud to ensure
        data privacy

    -   15 people among faculty members and managers, who are identified
        as the users of the dashboard software, are selected to evaluate
        the software.

    -   Users' satisfaction with the dashboard software is assessed
        using a Dashboard Assessment Usability Model.

    -   Usability Evaluation Criteria for Dashboards

        -   According to the review of other questionnaires used in
            previous studies, the following criteria are identified for
            dashboard evaluation: *usefulness, operability,
            learnability, ease of use, suitability for tasks,
            improvement of situational awareness, satisfaction, user
            interface, content, and system capabilities*

        -   Usefulness 

            -   Usefulness is usually defined as meeting a customer\'s
                needs or providing a competitive advantage with the
                product\'s attributes or benefits. Designers, generally,
                aim to deliver useful products. The "usefulness"
                criterion was used instead of "effectiveness and
                efficiency" to evaluate the usability of dashboards.

        -   Operability 

            -   It refers to a user\'s ability to use and control a
                dashboard for performing their tasks. In the present
                study, operability included criteria, such as
                representation of data in detail, access to various
                filters and reports, and ability to correct errors and
                support user. The user control is measured under the
                "operability" criterion.

        -   Learnability 

            -   Learnability is a quality of software interface that
                allows users to quickly become familiar with them and
                able to make good use of all their features and
                capabilities.

        -   Ease of Use 

            -   It is a fundamental concept explaining how easily users
                can employ a dashboard. This criterion was used for
                dashboard evaluation in the EUCS, Health-ITUES, and TAM
                questionnaires.

        -   Suitability for Tasks 

            -   This criterion can help to assess if users can find out
                whether a product or system is appropriate for their
                needs. It provides support for the users\' daily
                activities and ensures the compatibility and
                organization of data on the screen with the user\'s
                tasks.

        -   Improvement of Situational Awareness 

            -   Situation awareness at a fundamental level is about
                understanding what is going on and what might happen
                next. The criteria for evaluating situational awareness
                were divided into instability representation, complexity
                representation, variability representation, arousal
                support, concentration support, spare mental capacity
                support, and division of attention.

        -   Satisfaction 

            -   This criterion refers to satisfaction with the features,
                capabilities, and ease of use of a dashboard.

        -   User Interface 

            -   It consists of visual and interactive tools. Visual
                tools in a dashboard involve color coding for data
                visualization, histogram plots, pie charts, bar graphs,
                gauges, data labels, and geographic maps. The
                interactive techniques also include customizable
                searching, summary view, drill up and drill down, data
                ordering and filtering, zoom in and zoom out, and
                real-time feature.

        -   Content 

            -   This criterion involves the quantity and quality of data
                displayed by a dashboard. The quantity of displayed data
                was measured using two questionnaires (SART and PSSUQ),
                while quality was measured using SART. The amount of
                displayed data and their compatibility with the users\'
                tasks were also evaluated, and data accuracy, timeliness
                (being up-to-date), comprehensiveness, and relevance
                were used for measuring data quality.

        -   System Capabilities 

            -   Evaluation of compatibility is a criterion to assess
                software in terms of compatibility with work-related
                requirements. The dashboard capabilities are evaluated
                to determine how well its compatibility to work-related
                processes and how well it satisfies the users\' data
                requirements.

    -   The collected data will be analysed using descriptive statistics
        and data analysis software to suggest feedback and improvement
        as well as to assess large-scale deployability

# Final Product

-   The final product of this study is a GenAI powered dashboard for
    mostly automated grading with human involvement to providing
    facilities for instructors grade assignments much more efficiently
    based in teacher provided rubric and thus focus on the task of
    education.

-   The steps of designing this dashboard can be a basis for developing
    better dashboards for evaluating other faculties or even other
    universities.

## Definitions, Description of current shortcomings and needs

-   Assessing students' understanding from natural language responses,
    however, presents different challenges and has seen significant
    evolution

-   LLMs have been shown to outperform domain-specific language models

-   LLMs like GPT-4 could be useful for preliminary grading of
    introductory physics assignments, they fall short for
    natural-language responses required in comprehensive exam grading.

-   They also fall short on nuanced programming tasks and open-ended
    evaluation and therefore, in their current state, LLMs should be
    treated as a useful but fallible tool, with final assessments still
    in the hands of (human) instructors

-   It is also important to consider students perception of AI graders
    and how automated graders are deployed to educational settings 

-   Many comment on the socio-technical dynamics of automated grading,
    including the potential for introduction of machine bias

-   To address the evolving needs of grading open-ended responses, this
    framework proposes four key enhancements.

-   First, it is specifically designed for open-ended questions, which
    are not typically well-served by the simple, rubric-based grading of
    most ed-tech tools.

-   Second, the system leverages LLMs to deliver rapid, personalized
    feedback for student responses along with a quantitative grade as an
    addition that can be controlled.

-   Third, the framework introduces a feedback loop to continually
    improve instructor-provided prompts, question suggestions, and
    grading criteria.

-   Finally, the tool also integrates with the Jupyter Notebook
    environment, extensively utilized in fields such as computer
    science, data science, and statistics etc., for extensibility and
    modification to suit particular needs.

-   As a data management as well as decision support tool,
    conversationally enabled dashboards are one of the most effective
    and renowned forms of data objectification.

-   A dashboard can be defined as: "a tool for visualization that
    provides the possibility for acquiring awareness, finding trends,
    planning, and real comparisons.

-   These items are repeatedly embodied in a simple and functional user
    interface.

-   A dashboard of accumulated data effectively presents multiple
    sources and a comprehensive summary of important information that
    can be assimilated by faculty members at a glance, queried, directed
    to identify good question papers.

-   These dashboards enable organizations to measure, monitor,
    characterise and improve the performance of students while driving
    continuous instructional improvement.

-   These dashboards build on the foundations of business intelligence,
    data integration infrastructure, data science and Generative AI and
    are used for monitoring, analysis, and management and decision
    support.

-   Developing a grading assistant for a student specific, rubric
    included open ended performance evaluation, which is useful for
    quickly sharing with the students the information about their
    performance in a way that requires minimal effort from instructors
    represents enormous value.

-   Generating questions and evaluating the answers presented by
    students to generated questions based on lengthy content is
    time-consuming and exhausting when required to be done at scale for
    faculty members.

-   A dashboard, if designed appropriately with a conversational
    interface, can help instructors quickly evaluate answers that are
    compliant with course specific instructor provided rubric

-   Such an application enables educators to integrate open-ended
    questions into their curriculum without incurring an instructor
    labor cost.

-   This allows students to gain rapid, individualized, and
    sophisticated feedback, thereby creating a highly effective learning
    loop that can enhance the absorption of course materials.

-   It guides students in refining their responses, enhancing their
    understanding and application of concepts in each iteration.

-   This feedback is generated by a large language model (LLM), which
    circumvents the attentional errors often made by human graders,
    particularly when assessing a large volume of assignments.

-   The LLM is capable of delivering intricate responses to students
    swiftly

Approach Details

-   The effort will be carried out by the combined method of consecutive
    mixed designs.

-   In a sequential design, the data collection and data analysis of one
    component take place after the data collection and data analysis of
    the other component and depends on the outcomes of the other
    component.

-   Mixed Methods Research combines both closed-ended response data
    (quantitative) and open-ended personal data (qualitative).

-   The research environment is the Faculty of BITS. The study and
    software development must have obtained an ethical approval and will
    be conducted in four phases.

## Phase One: Identification of functional and non-functional requirements of Grading Assistant via interviews and systematic research 

-   The aim of this phase is to extract the functional parameters of the
    faculty, as well as the capabilities of the performance dashboard.

-   In this step, the research and interviews are performed using a
    combination of methods. The indicators of performance identified are
    divided into five different groups, including education, research,
    cultural and student affairs, resource management, and development &
    technology, each of which has its own performance indicators.

## Phase Two: Requirements Of the Grading Assistant Dashboard From The Perspective Of End Users

-   This phase is conducted in two steps.

-   In the first step, a qualitative study is conducted to identify the
    requirements of the dashboard software.

    -   For this purpose, eight educational group directors and faculty
        directors are selected by purposeful sampling for interviews.

    -   The average duration of each interview will be 30 minutes.

    -   At this stage, after coordinating with the interviewee and
        obtaining informed consent, the voice of the interview is
        recorded using an electronic recorder, and then its text is
        transcribed verbatim in Microsoft Word.

    -   The questions of the interview are related to the functional and
        non-functional requirements of the dashboard, gathering the
        course content as well as the information about the performance
        preferences of users.

    -   After transcription, the interviews are subjected to code
        extraction and then thematic analysis.

        -   Phase 1: Familiarizing yourself with the input data

        -   Phase 2: Obtaining initial content along with sample
            Questions, Answers and Grades

        -   Phase 3: Reviewing Educational content and Rubrics

        -   Phase 4: Identifying and grading responses

        -   Reviewing generated Grades and Personalized Responses

        -   Phase 6: Producing the report themes.

-   In the second step, a questionnaire is designed to identify the key
    performance indicators of the Grading Assistant using the two- round
    Delphi technique.

    -   Twenty individuals are purposefully selected among academic
        members, educational group directors, and faculty directors.

    -   In the first step of the Delphi technique, a questionnaire with
        three-choice questions (disagree, no opinion, and agree) and an
        open-ended question at the end of each section are completed, so
        people could state if they think anything should be added to the
        questionnaire for the second step of the Delphi technique.

    -   In the second step of the Delphi Technique, the indicators
        proposed are added and subjected to a poll.

    -   For data analysis, items with higher than 75% agreement are
        accepted, those with an agreement between 50--75% enter the
        second round of Delphi, and items with \< 50% agreement are
        omitted from the questionnaire.

## Phase Three: Software Development and Deployment

## 

-   For writing the code of this software, the Spanda Platform, Python
    and Web Technologies are used.

-   The interface of the software is designed using Html, JQuery, CSS,
    and Javascript languages to be run from standard browsers

-   Database software is used for designing tables and managing the
    database.

-   Private Cloud connectivity is available

## Phase Four~~[:]{.underline}~~ Evaluation Of User Satisfaction

-   In this phase, 15 of the academic members and managers of the
    faculty who are the users of the dashboard software are chosen.

-   In order to evaluate user satisfaction with the dashboard software,
    a 20 question Dashboard Assessment Usability Model scored based on a
    five-point Likert scale (1 = \"completely disagree\"; 5 =
    \"Completely agree\") will be used.

-   In addition, two open-ended questions are presented to the
    participants so that they can express their viewpoints and
    recommendations.

-   This scale will evaluate the dimensions of satisfaction (four
    questions), effectiveness (two questions), efficiency (two
    questions), operability ( ve questions), learnability (four
    questions), user interface aesthetics (one question), appropriate
    recognizability (one question), and accessibility (one question).

## Open-ended Questions

-   Is there any additional information besides the ones provided here
    that you would want to see in the dashboard?

-   Do you have any other comments or suggestions that you would like to
    share with us?

-   The validity and reliability of the questionnaire have been
    confirmed previously.

-   In the final step, the data are presented in tables using
    descriptive statistics such as frequency and percentage. Data
    analysis is conducted in Jupyter Notebook software.

# Ethic~~a~~l consider~~a~~tions

-   This study has been approved by the University Ethics Committee.

-   The confidentiality and anonymity of participants' information are
    strictly observed.

-   During interviews, participants' voices are recorded after obtaining
    their written informed consent.

-   Participants' information will not be disclosed in any publication
    form, and they will be clearly explained that they have the right to
    withdraw from the study at any time.

##  Brief Value Discussion 

-   This effort aims to design, implement and evaluate the effectiveness
    of a GenAI powered dashboard for AI Powered Human Involved grading
    and feedback provision to help improve instructor quality of life
    and resource management at the faculty level.

-   The steps used for developing this dashboard can provide a basis for
    designing better personalized education delivery for improvement of
    instructor quality of life and better evaluation of students.

-   Regarding the importance of information integration in organizations
    such as universities, it is essential to trace the flow and
    dimensions of information.

-   The lack of proper management of information resources can impede
    achieving organizational goals

-   Motivating instructor quality of life and quality of student
    evaluation via automation engines and graphical dashboards providing
    conversation interfaces, language models and generation engines is
    possible

-   Eliminating redundant work in different departments, retrieval of
    past generated grades and responses and finally, elimination of
    duplicate flowing of this information into multiple disparate
    organizational databases, which requires spending extra time and
    costs to reuse them is possible through this work.

-   The establishment and use of the generated information plays a
    significant role in the qualitative development of student
    evaluation methods and thus the transformation of the university
    into pioneers in the use of AI in education.

-   The information obtained from the information system provides a
    powerful management tool in the higher education system.

-   Despite the strengths of this approach, we may face some challenges
    while conducting various phases of this research.

-   For example, in phase one, participants may refuse full cooperation
    in completing the questionnaire or conducting the interview due to
    their busy work schedules.

-   We will try to distribute a considerable number of questionnaires
    among users to obviate this challenge.

-   During the implementation phase, the software designed may not be
    suitably integrated with other organizational systems, interfering
    with information exchange.

-   This challenge will be addressed by writing data processing
    pipelines that normalize and integrate data from various sources.
