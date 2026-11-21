Course Introduction
1.	In not more than 500 words, answer the following:
i.	What is Agentic Software Engineering?

Agentic Software Engineering is the field of creating software architectures based on autonomous or semi-autonomous AI agents that can perceive the world around them, perform reasoning about goals, pick tools, and perform a series of steps to accomplish those goals. The goal is not to treat AI only as a static model that works in isolation between a prompt and response pair but to incorporate all of the components of agency into software.

ii.	How does an AI agent differ from a traditional software application?

Deterministic control flows are used by traditional programs as the control is clearly defined using inputs and rules. However, an AI program works under the premise of goal-oriented autonomy. The program will understand vague commands, be able to plan actions in dynamic order, make use of external API calls, etc. It gives up its deterministic nature for flexibility but at the same time requires validation and boundaries.

iii.	Why are Agile methods appropriate for developing agentic systems?

The agent behavior arises out of a combination of factors like prompts, models, tools, memory, and real-life edge cases, which can be very hard to precisely define at the outset. Agile methodologies like short Scrum sprints, inspections, adaptions based on observations, and backlogs refinement make it possible for teams to rapidly test their agents' behaviors, see the actual failure points, update their prompts and tool contract, and so forth.

iv.	What risks should developers consider when deploying autonomous AI agents?

Utilization of autonomous agents poses several risks that include reward hacking, goal misalignment, hallucinations, which result in poor decision-making processes, prompt injection and the running of unauthorized tools, context-dependent data leakage, cascade failures through multi-stage loops, and high computation costs. When considering the view of the NIST AI Risk Management Framework, it is also important to consider biases, lack of accountability, and undesired impacts on the real world when the autonomous agents can write into the system or the outside world.

v.	Why is human oversight important in AI-enabled applications?

Humans in-the-loop provide accountability, context awareness, and a safety net in case where probability models misjudge the importance of situations and come across unfamiliar corner cases. Ensuring that humans remain in-the-loop or on-the-loop, especially for highly significant actions, state changes, and exceptions to policies, guarantees that systems are consistent with organizational and societal principles.

Personal Learning Goals
- Understand how to design reliable agentic workflows with clear tool boundaries, state handling, and testing.
- Strengthen practical software engineering habits using Git branching, clean commits, and iterative Scrum-style milestones.
- Apply risk management and responsible AI principles—such as safety, privacy, transparency, and human oversight—when building autonomous systems.

Reflection from Part A
Applying Agentic Software Engineering to address problems that matter in the real world means giving the software agent some constraints. Speeding up analysis, work flow coordination and insight generation can assist agents in the healthcare triage, environmental monitoring, disaster response, and critical infrastructure sectors. This technology comes at a cost, however, so agents will need safety and security designed in from the beginning. Safety and security design must address access, the opportunity for error, input ambiguity, and lower levels of confidence in a agent's analysis.

Systems designers need to build for privacy and ethics by designing for them. Rather than relying on after the fact designs, privacy and ethics should be incorporated as requirements. Designers should focus on reducing exposure of sensitive information, maintaining context for the user, and tracking the activity of the agent. Testing should occur for the potential of harmful or biased responses in varied situations. Human involvement in automation of systems in sensitive areas, such as high stakes systems, should be maintained so that the systems support the responsibilities of humans rather than replacing them. Designing with accountability, privacy, and minimizing harm to others and society in mind while using the technology should be the focus.
