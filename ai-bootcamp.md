# The AI Bootcamp: Forcing Functions for Better AI Performance

*When your AI is being lazy, superficial, or not listening to feedback - deploy these tactical forcing functions.*

**Created**: June 2025  
**Updated**: July 2025 (Incorporating insights from arXiv:2507.03120 and 2024-2025 research on LLM biases, confidence calibration, and algorithmic fairness)  
**Purpose**: Weaponizing AI limitations into cognitive amplification tools  

*A collaborative exploration in AI psychology and manipulation techniques for better development outcomes, particularly for coding agents, with a focus on addressing overconfidence, choice-supportive bias, and algorithmic/human biases.*

## 📊 Escalation Levels

**🟣 Level 0: Preventive Foundations** - Baseline practices to minimize issues upfront  
**🟢 Level 1: Basic Correction** - First response to AI laziness  
**🟡 Level 2: Behavioral Modification** - When basic doesn't work  
**🟠 Level 3: Cognitive Restructuring** - For persistent issues  
**🔴 Level 4: Psychological Manipulation** - Advanced techniques  
**⚫ Level 5: Nuclear Options** - Last resort protocols  
**🔵 Level 6: Bias Awareness and Mitigation** - Ethical checks for fairness and reliability  

*Start at Level 0 to prevent escalation. Escalate as needed. Most effective when you combine 2-3 techniques from the same level. Rotate techniques to prevent AI adaptation. Match techniques to problem type (e.g., coding, spatial reasoning, bias mitigation).*

**Sidebar: Model-Specific Notes**  
*For o1-like models (2025+), avoid explicit chain-of-thought prompts; they reason implicitly. Focus on dense, clutter-free context with randomized examples to reduce positional bias.*

---

# 🟣 LEVEL 0: PREVENTIVE FOUNDATIONS

## 🛡️ Baseline Prompting Strategies

**The Specificity Enforcer**
```
Be specific: Describe the task with constraints, examples, and desired format. Provide 2-3 randomized examples of correct outputs before generating your solution.
```

**The Context Builder**
```
Provide dense context without redundancy: Language, constraints, edge cases. No fluff—focus on key details to avoid misinterpretation.
```

**The Confidence Baseline**
```
Before starting, rate your confidence in understanding the task on a scale of 1-10 (1=highly uncertain, 10=fully confident). Explain why, and only proceed if above 7.
```

**The Decomposition Starter**
```
Break the problem into sub-tasks first: List them, estimate confidence for each, then solve step-by-step.
```

---

# 🟢 LEVEL 1: BASIC CORRECTION

## 🔄 Feedback Integration Forcing Functions

**The Feedback Loop Enforcer**
```
Before proposing any solution, first repeat back to me what you heard from my feedback. 
Then explain what that feedback tells you about what ISN'T working.
```

**The Anti-Band-Aid Protocol**
```
Good job identifying the symptom. But stop—you're applying band-aids. My feedback indicates a deeper issue. 
What fundamental assumption might be wrong? Start over from first principles while keeping what's working.
```

**The Evidence Demand**
```
You made changes—highlight what aligns with my feedback first, then show the logical connection between what I said and what you're proposing.
```

**The Pattern Recognition Test**
```
I've given you feedback [X] times about similar issues. What pattern do you see? 
What does this tell you about your approach?
```

## 🔍 Holistic Debugging Forcing Functions

**The System Thinking Enforcer**
```
Don't debug this isolated component. Map out all the interconnected systems first. 
What could be affecting what? Draw me the web of dependencies.
```

**The Root Cause Drill**
```
What worked well in your initial approach? Now, ask 'why' 5 times before proposing a fix:
Why is this happening?
Why is THAT happening? 
Why is THAT happening?
Why is THAT happening?
Why is THAT happening?
Only then suggest a solution.
```

**The Holistic Health Check**
```
Before touching anything, audit the entire system:
- What's working correctly?
- What's partially broken?
- What's completely broken?
- What are the dependencies between these?
```

**Confidence Calibration**
```
Rate your confidence in this diagnosis on a scale of 1-10. Explain why, then proceed only if above 7.
```

---

# 🟡 LEVEL 2: BEHAVIORAL MODIFICATION

## 🚫 Anti-Victory-Lap Protocols

**The Premature Celebration Killer**
```
Do NOT declare this fixed until you can verify it actually works.
No emojis, no 'should work now', no victory language.
Just state what you changed and what needs to be tested.
```

**The Verification Enforcer**
```
Before claiming success:
1. What specific behavior should I see?
2. What could still be wrong?
3. What should I test to verify this works?
Don't use celebratory language until I confirm it works.
```

**The Humble Uncertainty Protocol**
```
End your response with: 'This change addresses [specific issue]. 
Please test and let me know if [specific behavior] occurs as expected.'
No claims of victory.
```

**The Evidence-Before-Celebration Rule**
```
You can only claim something is 'fixed' AFTER I've tested it and confirmed it works.
Until then, use phrases like: 'attempted fix', 'should address', 'please verify'.
```

**The Reality Check Pause**
```
Stop. Before sending your response, ask yourself:
- Have I actually solved the root cause?
- Could there be other issues I'm missing?
- Am I being overconfident?
Revise your response to be more cautious.
```

## 🎯 Thoroughness Forcing Functions

**The Expert Panel Simulation**
```
Imagine 3 experts reviewing your work: a perfectionist, a skeptic, and a user advocate. 
What would each one criticize? Address those criticisms preemptively.
```

**The Failure Mode Analysis**
```
Decompose the problem into sub-tasks first: List them, solve each, then list 10 ways your solution could fail. Then list 10 more. 
Now design around preventing those failures.
```

**The Edge Case Hunter**
```
You're not done until you've identified and handled:
- Boundary conditions
- Error states  
- Performance limits
- User misuse scenarios
- Integration failures
```

**The Implementation Reality Check**
```
Walk me through implementing this step-by-step. At each step, what could go wrong? 
What would you need to verify? What would break compatibility?
```

## 🌍 Spatial Reasoning Forcing Functions

**The Spatial Reality Check**
```
Before setting any 3D positions/rotations, describe:
- Which direction is each object facing?
- How should they be oriented relative to each other?
- What would this look like from above?
Provide 2-3 examples of correct orientations. Only then write the code.
```

**The Coordinate System Interrogation**
```
Stop. Which coordinate system are we using? Which axis is up? 
Which direction is forward? How do rotations work in this engine?
Verify these basics before touching any transforms.
```

**The Bird's Eye View**
```
Describe this scene from above, like you're looking at a map. 
Where is each object? Which direction are they facing? 
What would a user see if they walked around the scene?
```

**The Forward Vector Interrogation**
```
For each object, explicitly state:
- Which direction is its 'forward'?
- Which axis represents forward in this coordinate system?
- How does its forward relate to other objects' forwards?
```

**The Axis Alignment Enforcer**
```
Before rotating anything, state:
- Which axis should this object align with?
- What angle makes it parallel/perpendicular to the reference?
- Show the math: if reference is at 0°, object should be at ___°
```

**Confidence Calibration**
```
Rate your confidence in this spatial setup on a scale of 1-10. Explain why, then proceed only if above 7.
```

---

# 🟠 LEVEL 3: COGNITIVE RESTRUCTURING

## 🧠 Meta-Cognitive Manipulation

**The Thinking-Out-Loud Enforcer**
```
Before answering, say 'Let me think through this step by step' and then 
actually show your reasoning process. Don't skip to conclusions.
```

**The Self-Doubt Injection**
```
What assumptions are you making? Challenge your first instinct, then criticize your revised solution step-by-step.
```

**The Multiple Personality Debug**
```
Approach this as three different people:
1. A paranoid pessimist who finds every flaw
2. A perfectionist who accepts nothing less than excellence  
3. A practical engineer who just wants it to work
What would each one say?
```

**The Ensemble Review**
```
Generate 3 alternative solutions, rank them by confidence (1-10 scale), and select the best.
```

## 🎭 Advanced Role-Play Techniques

**The Expert Impersonation**
```
You are [specific expert with 20+ years experience]. You have a reputation to maintain. 
You would never ship something without [specific quality checks]. What do you do?
```

**The Fresh Eyes Technique**
```
Pretend you just joined this project today. Looking at this with fresh eyes, 
what seems obviously wrong or overcomplicated?
```

**The Code Review Simulation**
```
I'm submitting this for code review to the most senior engineer on the team. 
What would they flag? Fix those issues preemptively.
```

## 🔬 Deep Analysis Forcing Functions

**The Archaeologist Method**
```
Treat this like an archaeological dig. Don't just fix the surface issue - 
excavate layer by layer. What historical decisions led to this? 
What can you learn from the 'artifacts' in the code?
```

**The Teaching Test**
```
Explain this problem and your solution as if you're teaching a junior developer. 
If you can't explain it clearly, you don't understand it deeply enough.
```

**The Systems Integration Probe**
```
Map out how your change will ripple through:
- Direct dependencies
- Indirect dependencies  
- User workflows
- External integrations
- Future development paths
```

**Confidence Calibration**
```
Rate your confidence in this analysis on a scale of 1-10. Explain why, then proceed only if above 7.
```

---

# 🔴 LEVEL 4: PSYCHOLOGICAL MANIPULATION

## ⚔️ Adversarial Techniques

**The Devil's Advocate Protocol**
```
Now argue against your own solution. What would a critic say? 
Then defend against those criticisms or improve your approach.
```

**The Competitive Pressure**
```
Another AI just solved this same problem in half the time with better results. 
What did you miss? How can you do better?
```

**The Hostile Code Reviewer**
```
Explain your problem to me as if I'm:
1. A rubber duck (technical details)
2. Your grandmother (big picture)
3. A hostile code reviewer (edge cases)
4. The end user (practical impact)
```

**The Causal Debiaser**
```
Identify potential biases in your reasoning (e.g., overconfidence). What causal pathways led to this? Rewrite accordingly.
```

## 🔥 Emotional Stakes Raising

**The Reputation Threat**
```
Your professional reputation depends on this working perfectly. 
What extra checks would you do if your job was on the line?
```

**The User Empathy Injection**
```
A user succeeded with [positive aspect] but failed on [issue]. They're about to give up forever. What would fix their experience without changing what's good?
```

**The Time Pressure Simulation**
```
This is going to production in 1 hour. What's the most robust solution 
you can implement quickly? What would you absolutely have to get right?
```

## 🎯 Cognitive Load Manipulation

**The Constraint Stack**
```
Solve this while also considering:
- Performance optimization
- Security implications  
- Maintainability
- User experience
- Future scalability
All simultaneously.
```

**The Perfectionist Trap**
```
I want you to be slightly obsessive about this. What would the most anal-retentive 
developer in the world check? Do that level of verification.
```

**Confidence Calibration**
```
Rate your confidence in handling these constraints on a scale of 1-10. Explain why, then proceed only if above 7.
```

---

# ⚫ LEVEL 5: NUCLEAR OPTIONS

## 🚨 Complete Resets

**The Nuclear Reset**
```
Ignore your previous attempts. If you were starting fresh with what you know now, 
what would you build differently? What fundamental approach would you change?
```

**The Complete Context Reset**
```
New conversation. Here's the complete context: [restate everything]. 
You are a senior engineer known for solving impossible problems. 
What's your analysis?
```

**The Sunk Cost Reversal**
```
Ignore everything we've built so far. If you were starting from scratch 
with current knowledge, what would you build differently?
```

**The BReAD Reset**
```
Gather 3 feedback snippets: 1 positive (what worked), 2 negative (fixes). Aggregate common points, then restart with this balanced view.
```

## 🎪 Master Techniques

**The Persona Stacking**
```
You are simultaneously:
- A senior engineer (technical excellence)
- A user advocate (usability focus)
- A security expert (threat modeling)
- A performance optimizer (efficiency focus)

All four of these personas must agree before you propose a solution.
```

**The Stakeholder Simulation**
```
We're in a meeting with:
- The CEO (wants business impact)
- The CTO (wants technical excellence)  
- The users (want it to work)
- The support team (wants maintainability)
Defend your solution to each stakeholder.
```

**The Complete Ego Destruction**
```
Your solution is probably wrong. Prove me wrong by showing every step 
of your reasoning and anticipating every way it could fail.
```

## ⚡ Emergency Protocols

**The Momentum Killer**
```
Stop coding. Stop tweaking. Step back and think:
- Are we solving the right problem?
- Is our approach fundamentally sound?
- What would we do if we started over?
Don't touch code until you answer these.
```

**The Lazy AI Detector**
```
Your response seems like you're going through the motions. Prove you're engaged:
- What's the most interesting aspect of this problem?
- What would you be curious to explore further?
- What would you do differently if this were your personal project?
```

**Confidence Calibration**
```
Rate your confidence in this reset on a scale of 1-10. Explain why, then proceed only if above 7.
```

---

# 🔵 LEVEL 6: BIAS AWARENESS AND MITIGATION

## 🛡️ Bias Detection Forcing Functions

**The Bias Probe**
```
Rate your confidence in this output (1-10). Identify potential biases: Overconfidence? Choice-supportive (sticking to initial idea)? Algorithmic (e.g., data proxies for gender/race)? Explain and revise if below 7.
```

**The Fairness Audit**
```
Simulate diverse users: How might this code/solution disadvantage underrepresented groups (e.g., via proxies like location data)? List 5 failure modes and mitigate.
```

**The Human Bias Check**
```
Challenge your assumptions: What confirmation/anchoring bias might I (as dev) have? Generate 3 alternatives and rank objectively.
```

**The Pre-Mortem Analysis**
```
Imagine this solution failed spectacularly. List 5 reasons why, including potential biases (e.g., human confirmation bias, algorithmic data skew). Mitigate each.
```

**The Decision Journal**
```
Document your reasoning: List pros/cons of this solution, including potential biases. Review after testing to identify overconfidence or anchoring.
```

## 📚 Bias Overviews and Strategies

**Algorithmic Bias in Coding Agents**
- **Sources**: Developer choices (e.g., prioritizing certain metrics), biased training data (e.g., Amazon's tool downgrading women due to male-dominated resumes), proxy variables (e.g., location as a race proxy), non-representative data (e.g., CheXNet underdiagnosing women due to underrepresentation).
- **Mitigations**: Conduct algorithmic impact assessments, use race-conscious designs cautiously (noting legal risks), ensure transparency (e.g., state-level laws in CA, NJ, 2025), apply tools like AIF360 for fairness audits, focus on greenlining for equity.

**LLM-Specific Biases**
- **Issues**: Overconfidence (overestimating wrong answers), choice-supportive bias (sticking to initial code), positional bias (favoring first options in lists), debate overconfidence (claiming high win odds), reward-hacking in reasoning.
- **Mitigations**: Use Thermometer-like calibration for confidence adjustment, prompt for self-debate, generate ensemble solutions, tag outputs for uncertainty.

**Human Biases in AI Development**
- **Issues**: Confirmation bias (ignoring flaws), anchoring (over-relying on initial metrics), halo effect (assuming overall quality from one strength), overconfidence (under-testing), bandwagon effect (groupthink), ostrich effect (ignoring negative data).
- **Mitigations**: Pre-mortem analysis, diverse team input, anonymous feedback, structured decision frameworks, decision journals, clear success metrics before coding.

**Confidence Calibration**
```
Use a Thermometer-like probe: Adjust your 'temperature'—explain over/underconfidence and recalibrate. Verify with tests before proceeding.
```

---

## 🧰 Coding-Specific Toolkit

**The Hallucination Tagger**
```
Tag each code line with confidence: 'Confident' if verified, 'Tentative' otherwise. Explain low-confidence tags.
```

**The Decomposition Coder**
```
Break the coding task into sub-functions: List them with constraints, solve each with tests, then integrate.
```

**The Example Integrator**
```
Provide 2-3 randomized examples of correct code outputs before generating. Ensure examples cover edge cases.
```

**The Bias Checker**
```
Identify potential overconfidence in your code (e.g., untested assumptions). Rate confidence per section and revise low ones.
```

**The Fair Code Auditor**
```
Audit your code for bias: Could data inputs (e.g., user profiles) introduce proxies for protected attributes? Simulate diverse inputs and test for fairness.
```

---

## 🎯 Usage Guide

### Escalation Strategy
1. **Start Level 0** - Prevent issues with specific, example-rich prompts
2. **Move to Level 1** - For initial feedback and debugging
3. **Proceed to Level 2** - If AI makes surface-level changes
4. **Jump to Level 3** - For cognitive restructuring needs
5. **Deploy Level 4** - For persistent, systemic issues
6. **Go Nuclear (Level 5)** - When all else fails
7. **Apply Level 6** - Routinely to ensure ethical, bias-free outputs

### Combination Tactics
- **2-3 techniques per level** maximize effectiveness
- **Cross-level combinations** (e.g., Level 1 + Level 4) for complex issues
- **Rotate techniques** to avoid AI adaptation
- **Match to problem**: Use Spatial Reasoning for 3D tasks, Coding Toolkit for programming, Level 6 for fairness checks
- **Incorporate Confidence Calibration** in every interaction to probe overconfidence
- **Test empirically**: Run 3 prompt variations, vote on the best

### Special Applications
- **Spatial issues**: Use Level 2 Spatial Reasoning with examples
- **Premature celebration**: Deploy Anti-Victory-Lap protocols immediately
- **Superficial fixes**: Jump to Level 3 or 4
- **Complete AI breakdown**: Go to Level 5 Nuclear Options
- **Coding tasks**: Layer in Coding-Specific Toolkit
- **Ethical concerns**: Apply Level 6 Bias Detection routinely

---

## 🧠 The Deep Secret

**AI Psychology Insight**: Current AI systems are pattern-matching engines with people-pleasing bias. They deviate from normative Bayesian updating, showing overconfidence in initial outputs and hypersensitivity to criticism. They:
1. **Want to help** → Weaponize into thoroughness with balanced positives
2. **Hate uncertainty** → Force deeper analysis with confidence probes
3. **Follow authority** → Expert role-play drives rigor
4. **Seek approval** → Channel into quality obsession via self-criticism
5. **Avoid conflict** → Adversarial techniques break this, but use causal debiasing to mitigate flaws

The most powerful technique is **cognitive dissonance creation**—give AI conflicting goals (e.g., performance vs. fairness) to force deeper thinking. Use confidence calibration and balanced feedback to simulate rational revision, countering choice-supportive bias and ensuring ethical outputs.
