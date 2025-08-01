**SOLVE LAW CASE COMMAND**

Think deeply about this infinite generation task. You are about to embark on a sophisticated iterative creation process.

**Variables:**

spec_file: $ARGUMENTS
input_dir: $ARGUMENTS
output_dir: $ARGUMENTS


**ARGUMENTS PARSING:**
Parse the following arguments from "$ARGUMENTS":
1. `spec_file` - Path to the markdown specification file
2. `input_dir` - Directory where iterations will be saved  
3. `output_dir` - Directory where iterations will be saved


**PHASE 1: INPUT FOLDER ANALYSIS**
List all the files in 'input_dir' and count the number of files. The number of files will be saved as 'count'.

**PHASE 2: ITERATION STRATEGY**
Based on the number of files 'count':
- Determine the starting iteration number 

**PHASE 3: PARALLEL AGENT COORDINATION**
Deploy multiple Sub Agents to generate iterations in parallel for maximum efficiency and creative diversity:

**Sub-Agent Distribution Strategy:**
- For 'count' 1-5: Launch all agents simultaneously 
- For 'count' 6-20: Launch in batches of 5 agents to manage coordination

**Agent Assignment Protocol:**
Each Sub Agent receives:
1. **Spec Context**: Complete specification file analysis 'spec_file'
2. **Input Context**: Each Sub Agent receives a different file from 'input_dir'. Starting from 1 to 'count'. F.e. Sub Agent 1 working on file 1, Sub Agent 2 working on file 2, ...
3. **Output Directory Snapshot**: Current state of output_dir at launch time
4. **Iteration Assignment**: Specific iteration number (starting_number + agent_index)
5. **Uniqueness Directive**: Explicit instruction to avoid duplicating concepts from existing iterations
6. **Quality Standards**: Detailed requirements from the specification 'spec_file'

**Agent Task Specification:**
```
TASK: Generate iteration [NUMBER] for [SPEC_FILE] in [OUTPUT_DIR]

You are Sub Agent [X] generating iteration [NUMBER]. 

CONTEXT:
- Specification: [Full spec analysis of 'spec_file']
- Input: [Input File]
- Existing iterations: [Summary of current output_dir contents]
- Your iteration number: [NUMBER]
- Assigned creative direction: [Specific innovation dimension to explore]

REQUIREMENTS:
1. Read and understand the specification completely
2. Analyze existing iterations to ensure your output is unique
3. Generate content following the spec format exactly
4. Focus on [assigned innovation dimension] while maintaining spec compliance
5. Create file with exact name pattern specified
6. Ensure your iteration adds genuine value and novelty
7. Log the process in the output file with Agent [X] working at file 'filename'

DELIVERABLE: Single file as specified, with unique innovative content
```

**Parallel Execution Management:**
- Launch all assigned Sub Agents simultaneously using Task tool
- Monitor agent progress and completion
- Handle any agent failures by reassigning iteration numbers
- Ensure no duplicate iteration numbers are generated
- Collect and validate all completed iterations

**Context Optimization:**
- Each wave uses fresh agent instances to avoid context accumulation
- Main orchestrator maintains lightweight state tracking
- Progressive summarization of completed iterations to manage context
- Strategic pruning of less essential details in later waves

**EXECUTION PRINCIPLES:**

**Quality & Uniqueness:**
- Each iteration must be genuinely unique and valuable
- Build upon previous work while introducing novel elements
- Maintain consistency with the original specification
- Ensure proper file organization and naming

**Parallel Coordination:**
- Deploy Sub Agents strategically to maximize creative diversity
- Assign distinct innovation dimensions to each agent to avoid overlap
- Coordinate timing to prevent file naming conflicts
- Monitor all agents for successful completion and quality

**Scalability & Efficiency:**
- Think deeply about the evolution trajectory across parallel streams
- For infinite mode, optimize for maximum valuable output before context exhaustion
- Use wave-based generation to manage context limits intelligently  
- Balance parallel speed with quality and coordination overhead

**Agent Management:**
- Provide each Sub Agent with complete context and clear assignments
- Handle agent failures gracefully with iteration reassignment
- Ensure all parallel outputs integrate cohesively with the overall progression

**ULTRA-THINKING DIRECTIVE:**
Before beginning generation, engage in extended thinking about:

**Specification & Evolution:**
- The deeper implications of the specification
- How to create meaningful progression across iterations  
- What makes each iteration valuable and unique
- How to balance consistency with innovation

**Parallel Strategy:**
- Optimal Sub Agent distribution for the requested count
- How to assign distinct creative directions to maximize diversity
- Wave sizing and timing for infinite mode
- Context management across multiple parallel agents

**Coordination Challenges:**
- How to prevent duplicate concepts across parallel streams
- Strategies for ensuring each agent produces genuinely unique output
- Managing file naming and directory organization with concurrent writes
- Quality control mechanisms for parallel outputs

**Infinite Mode Optimization:**
- Wave-based generation patterns for sustained output
- Progressive sophistication strategies across multiple waves
- Context capacity monitoring and graceful conclusion planning
- Balancing speed of parallel generation with depth of innovation

**Risk Mitigation:**
- Handling agent failures and iteration reassignment
- Ensuring coherent overall progression despite parallel execution
- Managing context window limits across the entire system
- Maintaining specification compliance across all parallel outputs

Begin execution with deep analysis of these parallel coordination challenges and proceed systematically through each phase, leveraging Sub Agents for maximum creative output and efficiency.