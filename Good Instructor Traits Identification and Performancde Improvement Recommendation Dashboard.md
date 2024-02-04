
# Specification, Design and development of a Conversation GenAI powered Dashboard with a recommendation engine for Identification of the Traits of a Good Instructor and for suggesting improvement approaches based on the traits of the top performers

# Background

-   Instructors within an educational system, comprises a combination of
    various educational groups, faculty members, researchers, students,
    as well as administrative staff.

-   Each group of faculty members contributes to different fields.

-   The management of all data records related to the performance and
    activities of the faculty and its members leads to better
    monitoring, identification of weaknesses, strengths and the traits
    of a "good" instructor from the top performers allowing the
    educational institution to characterize instructors which can be
    used to improve the overall performance of the faculty.

-   A conversationally enabled analytical dashboard is the primary
    interaction tool that is used for monitoring and metricizing faculty
    performance and using it to identify the traits of good instructors.

# Objectives of the Effort

The objective of this effort is to develop a functional,
conversationally driven dashboard for the faculty of BITS and metricize
and identify the traits of a good instructor and use that to suggest
improvements in its teaching staff's efficacy.

# Effort Approach and Phases

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
        GenAI powered dashboard along with the associated retrieval
        augmented language model and the recommendation engine is
        developed using Python programming language in an IDE

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

-   The Final product of this study is a GenAI powered dashboard for
    monitoring, evaluating performance, characterizing a "good"
    instructor and providing improvement recommendations to supporting
    the improvement of instructors and resources at the faculty level.

-   The steps of designing this dashboard can be a basis for developing
    better dashboards for evaluating other faculties or even other
    universities.

## Definitions, Description of current shortcomings and needs

-   A faculty, as an educational system, consists of a combination of
    various educational groups, faculty members, researchers, students,
    and administrative staff.

-   Each faculty member contributes to different areas (teaching,
    research, and management).

-   A faculty is a place where different types of courses, learning
    activities, conferences and conventions are held.

-   The data related to these activities with the participation of
    faculty members are facts and information resulting from academic
    activities.

-   The data of a faculty refers to the information linked with the
    academic performance of its instructors and lecturers, such as the
    details of academic services and contributions, courses completed,
    student evaluations provided, the number of annual research
    publications, and the number of committees in which the faculty
    member is a member of etc.

-   Although the collection, management, and reporting of faculty data
    is crucial for each faculty member, as well as for the institution
    itself as a complete establishment, numerous gaps exist in this
    area.

-   While a faculty member may be involved in several activities, most
    of these activities are not documented and recognized because
    universities lack a central system for effectively recording these
    data and presenting a comprehensive report of such activities and
    performance feedback that can be used to guide faculty performance
    improvement.

-   Currently, typically in many universities, different independent
    systems host faculty data. The lack of internal communication
    between these systems causes these data to be enclosed in a
    contained silo.

-   Retrieving data from multiple systems is often a manual and a
    difficult process for administrative staff and faculty members.

-   As these data are not analysed using Generative AI techniques or
    merged to provide an integrated picture, their trends and
    inter-relationships cannot be exploited

-   This is a lost opportunity

    -   to acquire data

    -   to discover information

    -   extract knowledge about instructors and their methods

    -   identify the traits of good instructors from the top performers

    -   using those identified traits to recommend performance
        improvement using AI powered recommender systems)

    -   Positively impacting the overall quality of education delivered.

-   Currently, the data recording aspect is inconsistent and inadequate
    in most higher education institutions,

-   There also is only partial automation in terms of recording and
    sharing data between different systems and constituents.

-   Therefore, faculty members and managers spend a lot of time and
    effort in manual data entry to gather or track the details of
    academic activities and drive their assessments and performance
    improvements.

-   Despite the fact that the manual entering of data is unavoidable in
    some cases, use of intelligent automation, enabling interoperability
    between systems to prevent the duplicate recording of data and use
    of AI to enable dashboards is not well implemented today.

-   In addition, faculty members have inadequate time and skills to
    perform statistical analyses on data (e.g., findings correlations,
    querying, recommendations etc.) and extrapolate valuable
    interpretations, targeted feedback, or practical complementary
    objectives as the dashboards are poorly design and do not provide
    easy to use conversational interfaces or AI powered engines.

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
    to identify traits of "good" instructors based on top performers.

-   These dashboards enable organizations to measure, monitor,
    characterise and improve the performance of faculty members and
    drive continuous improvement using various recommendation methods
    more effectively.

-   These dashboards build on the foundations of business intelligence,
    data integration infrastructure, data science and Generative AI and
    are used for monitoring, analysis, and management and decision
    support.

-   Developing a faculty performance evaluation, benchmarking and
    improvement dashboard is useful for quickly sharing with faculty
    members information about their performance in a way that requires
    minimal effort and helps them better understand the data by querying
    the data using language-based interfaces (chatbots) and asking for
    suggestions on improvement (recommendation engines) as well as
    identifying those traits (Factor Analysis, Causal Analysis) that can
    be used to identify an effective teacher.

-   Observing, querying and interpreting the data presented in large
    tables and lengthy reports are exhausting and time-consuming for
    faculty members. In other words, a dashboard, if designed
    appropriately with conversational interfaces, can help faculty
    members quickly spot their strengths and areas of progress and
    identify the trends and steps necessary for improvement and
    recommend/suggest methods for improvement.

-   Based on the current state explorations, there are substantial gaps
    in the reporting and management of faculty data.

-   Therefore, it is necessary to develop a comprehensive dashboard for
    monitoring and evaluating the performance of instructors across
    various activities such as education, research, cultural fit,
    student affairs participation, resource management effectiveness and
    technology development.

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

## Phase One: Identification of functional and non-functional requirements of performance dashboards and performance indicators and traits of good instructors through interviews and systematic research 

-   The aim of this phase is to extract the functional parameters of the
    faculty, as well as the capabilities of the performance dashboard.

-   In this step, the research and interviews are performed using a
    combination of methods. The indicators of performance identified are
    divided into five different groups, including education, research,
    cultural and student affairs, resource management, and development &
    technology, each of which has its own performance indicators.

## Phase Two: Requirements Of the Instructor Traits Dashboard From The Perspective Of Users

-   This phase is conducted in two steps.

-   In the first step, a qualitative study is conducted to identify the
    requirements of the performance dashboard software.

    -   For this purpose, eight educational group directors and faculty
        directors are selected by purposeful sampling for interviews.

    -   The average duration of each interview will be 30 minutes.

    -   At this stage, after coordinating with the interviewee and
        obtaining informed consent, the voice of the interview is
        recorded using an electronic recorder, and then its text is
        transcribed verbatim in Microsoft Word.

    -   The questions of the interview are related to the functional and
        non-functional requirements of the dashboard, as well as the
        performance preferences of users.

    -   After transcription, the interviews are subjected to code
        extraction and then thematic analysis.

        -   Phase 1: Familiarizing yourself with your data

        -   Phase 2: Generating initial codes

        -   Phase 3: Searching for themes

        -   Phase 4: Reviewing themes

        -   Phase 5: Defining and naming

        -   Phase 6: Producing the report themes.

-   In the second step, a questionnaire is designed to identify the key
    performance indicators of the faculty using the two- round Delphi
    technique.

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
    of a GenAI powered performance dashboard for functional monitoring,
    evaluation, and identification of traits of a good instructor to
    help improve instructor performance and resource management at the
    faculty level.

-   The steps used for developing this dashboard can provide a basis for
    designing better performance trait identification and recommendation
    engines for improvement of instructor performance based on the
    trairs of good instructors gleaned by analysis of top instructors.

-   Regarding the importance of information integration in organizations
    such as universities, it is essential to trace the flow and
    dimensions of information.

-   The lack of proper management of information resources can impede
    the efficient identification of the traits of good teachers from the
    top performers and thus hinder achieving organizational goals

-   Motivating instructor improvement by working with integrated
    information presented via graphical dashboards and using
    conversation interfaces, language models and recommendation engines
    is possible

-   Eliminating redundant work in different departments, retrieval of
    similar information, and finally, duplicate flowing of this
    information into multiple organizational databases, which requires
    spending extra time and costs to reuse them is possible through this
    work.

-   The establishment and use of comprehensive information resources
    play a strategic role in the qualitative development of universities
    instructional staff and their transformation into pioneer
    organizations and contribute a substantial role in achieving the
    strategic goals of the university.

-   The information obtained from the information system provides a
    powerful management tool in the higher education system.

-   Because of providing timely and accurate information, AI powered
    conversation dashboards with integrated recommendation systems are
    considered the most powerful systems to fulfill the informational
    needs of organizations, including universities, and to handle bulk
    amounts of organizational data about insttructiors.

-   Performance Improvement can be achieved based on the identification
    of the traits of the top faculty performers through a performance
    dashboard, and using a recommendation engine in combination with a
    performance coaching process through which the function of
    instructors is formally and regularly assessed at certain intervals
    to ensure continuous improvement.

-   Evaluation of the performance of academic members refers to the
    regular assessment of their educational/research activities and
    determining to what extent the goals of the educational system,
    according to predetermined criteria, can be achieved.

-   Functional monitoring refers to the real-time observation of the
    faculty's key performance indicators.

-   Faculty resource management encompasses being informed of the
    current situation of human resources and equipment and figuring out
    optimal ways of deploying them to improve overall faculty
    performance.

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
