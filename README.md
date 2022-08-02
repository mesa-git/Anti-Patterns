NOTE: Done because some "mod" on wikipedia decided "first of all, "lists of examples" are not always encyclopedic; they are more a trash can."
The original page was here: https://en.wikipedia.org/w/index.php?title=Anti-pattern
So here's the trash can:

<br><br>
# Anti-Patterns

### Organizational

- [Analysis paralysis](https://en.wikipedia.org/wiki/Analysis_paralysis): A project that has stalled in the analysis phase of development, and is unable to achieve support for any of the potential plans of its implementation

- [Bicycle shed](https://en.wikipedia.org/wiki/Law_of_triviality): Giving disproportionate weight to trivial issues

- [Bleeding edge](https://en.wikipedia.org/wiki/Law_of_triviality): Operating with cutting-edge technologies that are still untested or unstable, leading to cost overruns, under-performance or delayed delivery of the product
    
- [Bystander apathy](https://en.wikipedia.org/wiki/Bystander_effect): The phenomenon in which people are less likely to or do not offer help to a person in need when others are present
    
- [Cash cow](https://en.wikipedia.org/wiki/Cash_cow): A profitable legacy product that often leads to complacency about new products
- [Design by committee](https://en.wikipedia.org/wiki/Design_by_committee): The result of having many contributors to a design, but no unifying vision
- [Escalation of commitment](https://en.wikipedia.org/wiki/Escalation_of_commitment): Failing to revoke a decision when it proves wrong
- [Groupthink](https://en.wikipedia.org/wiki/Groupthink): A collective state where group members begin, often unknowingly, to think alike and reject differing viewpoints
- [Management by objectives](https://en.wikipedia.org/wiki/Management_by_objectives) ([SAFe](https://en.wikipedia.org/wiki/Scaled_agile_framework)): Management operating with the exclusive focus on quantitative management criteria, such as number of sales, when these are non-essential or cost too much to acquire
- [Micromanagement](https://en.wikipedia.org/wiki/Micromanagement): Ineffective results stemming from excessive observation, supervision, or other hands-on involvement from management
- [Moral hazard](https://en.wikipedia.org/wiki/Moral_hazard): Insulating a decision-maker from the consequences of their decision
- [Mushroom management](https://en.wikipedia.org/wiki/Mushroom_management): Keeping employees "in the dark and fed manure" (also "left to stew and finally canned") about decisions being taken by management
- [Peter principle](https://en.wikipedia.org/wiki/Peter_principle): Continually promoting otherwise well-performing employees up to a position they are unsuited for, with responsibilities they are incompetent at completing, where they remain indefinitely.
- [Seagull management](https://en.wikipedia.org/wiki/Seagull_management): Management in which managers only interact with employees when a problem arises, when they "fly in, make a lot of noise, dump on everyone, do not solve the problem, then fly out"
- [Stovepipe or Silos](https://en.wikipedia.org/wiki/Stovepipe_(organisation)): An organizational structure of isolated or semi-isolated teams, in which too many communications take place up and down the hierarchy, rather than directly with other teams across the organization
- [Typecasting](https://en.wikipedia.org/wiki/Typecasting): Locking successful employees into overly-safe, narrowly defined, predictable roles based on their past successes rather than their potential
- [Vendor lock-in](https://en.wikipedia.org/wiki/Vendor_lock-in): Making a system excessively dependent on an externally supplied component.

### Project management

- [Cart before the horse](https://en.wikipedia.org/wiki/Cart_before_the_horse): Focusing too many resources on a stage of a project out of its sequence
- [Death march](https://en.wikipedia.org/wiki/Death_march_(project_management)): A project whose staff, while expecting it to fail, are compelled to continue, often with much overwork, by management in denial of the project's possible failure
- [Ninety-ninety rule](https://en.wikipedia.org/wiki/Ninety%E2%80%93ninety_rule): Tendency to underestimate the amount of time to complete a project when it is "nearly done"
- [Overengineering](https://en.wikipedia.org/wiki/Overengineering): Spending resources making a project more robust and complex than is needed
- [Scope creep](https://en.wikipedia.org/wiki/Scope_creep): Uncontrolled changes or continuous growth in a project's scope, or adding new features to the project after the original requirements have been drafted and accepted (also known as requirement creep and feature creep)
- [Smoke and mirrors](https://en.wikipedia.org/wiki/Smoke_and_mirrors): Demonstrating unimplemented functions as if they were already implemented
- [Brooks's law](https://en.wikipedia.org/wiki/Brooks%27s_law): Adding more resources to a project to increase velocity, when the project is already slowed by coordination overhead
- [Gold plating](https://en.wikipedia.org/wiki/Gold_plating_(project_management)): Continuing to work on a task or project well past the point at which extra effort is not adding value

### Software design

- [Abstraction inversion](https://en.wikipedia.org/wiki/Abstraction_inversion): Not exposing implemented functionality required by callers of a function/method/constructor, so that the calling code awkwardly re-implements the same functionality in terms of those calls
- [Ambiguous viewpoint](https://en.wikipedia.org/wiki/Ambiguous_viewpoint): Presenting a model (usually Object-oriented analysis and design (OOAD)) without specifying its viewpoint
- [Big ball of mud](https://en.wikipedia.org/wiki/Big_ball_of_mud): A system with no recognizable structure
- [Database-as-IPC](https://en.wikipedia.org/wiki/Database-as-IPC): Using a database as the message queue for routine interprocess communication where a much more lightweight mechanism would be suitable
- [Inner-platform effect](https://en.wikipedia.org/wiki/Inner-platform_effect): A system so customizable as to become a poor replica of the software development platform
- [Input kludge](https://en.wikipedia.org/wiki/Input_kludge): Failing to specify and implement the handling of possibly invalid input
- [Interface bloat](https://en.wikipedia.org/wiki/Interface_bloat): Making an interface so powerful that it is extremely difficult to implement
- [Magic pushbutton](https://en.wikipedia.org/wiki/Magic_pushbutton): A form with no dynamic validation or input assistance, such as dropdowns
- [Race hazard (or race condition)](https://en.wikipedia.org/wiki/Race_condition): Failing to see the consequences of events that can sometimes interfere with each other.
- [Stovepipe system](https://en.wikipedia.org/wiki/Stovepipe_system): A barely maintainable assemblage of ill-related components

### Object-oriented programming

- [Anemic domain model](https://en.wikipedia.org/wiki/Anemic_domain_model): The use of the domain model without any business logic. The domain model's objects cannot guarantee their correctness at any moment, because their validation and mutation logic is placed somewhere outside (most likely in multiple places). Martin Fowler considers this to be an anti-pattern, but some disagree that it is always an anti-pattern.
- [Call super](https://en.wikipedia.org/wiki/Call_super): Requiring subclasses to call a superclass's overridden method
- [Circle–ellipse problem](https://en.wikipedia.org/wiki/Circle%E2%80%93ellipse_problem): Subtyping variable-types on the basis of value-subtypes
- [Circular dependency](https://en.wikipedia.org/wiki/Circular_dependency): Introducing unnecessary direct or indirect mutual dependencies between objects or software modules
- [Constant interface](https://en.wikipedia.org/wiki/Constant_interface): Using interfaces to define constants
- [God object](https://en.wikipedia.org/wiki/God_object): Concentrating too many functions in a single part of the design (class)
- [Object cesspool](https://en.wikipedia.org/wiki/Object_pool_pattern#Pitfalls): Reusing objects whose state does not conform to the (possibly implicit) contract for re-use
- [Object orgy](https://en.wikipedia.org/wiki/Object_orgy): Failing to properly encapsulate objects permitting unrestricted access to their internals
- [Poltergeists](https://en.wikipedia.org/wiki/Poltergeist_(computer_programming)): Objects whose sole purpose is to pass information to another object
- [Sequential coupling](https://en.wikipedia.org/wiki/Sequential_coupling): A class that requires its methods to be called in a particular order
- [Yo-yo problem](https://en.wikipedia.org/wiki/Yo-yo_problem): A structure (e.g., of inheritance) that is hard to understand due to excessive fragmentation

### Programming

- [Accidental complexity](https://en.wikipedia.org/wiki/No_Silver_Bullet): Programming tasks that could be eliminated with better tools (as opposed to essential complexity inherent in the problem being solved)
- [Action at a distance](https://en.wikipedia.org/wiki/Action_at_a_distance_(computer_programming)): Unexpected interaction between widely separated parts of a system
- [Boat anchor](https://en.wikipedia.org/wiki/Boat_anchor_(metaphor)): Retaining a part of a system that no longer has any use
- [Busy waiting](https://en.wikipedia.org/wiki/Busy_waiting): Consuming CPU while waiting for something to happen, usually by repeated checking instead of messaging
- [Caching failure](https://en.wikipedia.org/wiki/Negative_cache): Forgetting to clear a cache that holds a negative result (error) after the error condition has been corrected
- [Cargo cult programming](https://en.wikipedia.org/wiki/Cargo_cult_programming): Using patterns and methods without understanding why
- [Coding by exception](https://en.wikipedia.org/wiki/Coding_by_exception): Adding new code to handle each special case as it is recognized
- [Error hiding](https://en.wikipedia.org/wiki/Error_hiding): Catching an error message before it can be shown to the user and either showing nothing or showing a meaningless message. This anti-pattern is also named Diaper Pattern. Also can refer to erasing the Stack trace during exception handling, which can hamper debugging.
- [Hard code](https://en.wikipedia.org/wiki/Hard_coding): Embedding assumptions about the environment of a system in its implementation
- [Lasagna code](https://en.wikipedia.org/wiki/Spaghetti_code#Lasagna_code): Programs whose structure consists of too many layers of inheritance
- [Lava flow](https://en.wikipedia.org/wiki/Lava_flow_(programming)): Retaining undesirable (redundant or low-quality) code because removing it is too expensive or has unpredictable consequences[9][10]
- [Loop-switch sequence](https://en.wikipedia.org/wiki/Loop-switch_sequence): Encoding a set of sequential steps using a switch within a loop statement
- [Magic numbers](https://en.wikipedia.org/wiki/Magic_number_(programming)#Unnamed_numerical_constants): Including unexplained numbers in algorithms
- [Magic strings](https://en.wikipedia.org/wiki/Magic_string#Magic_strings_in_code): Implementing presumably unlikely input scenarios, such as comparisons with very specific strings, to mask functionality.
- [Repeating yourself](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself): Writing code that contains repetitive patterns and substrings over again; avoid with once and only once (abstraction principle)
- [Shooting the messenger](https://en.wikipedia.org/wiki/Shooting_the_messenger): Throwing exceptions from the scope of a plugin or subscriber in response to legitimate input, especially when this causes the outer scope to fail.
- [Shotgun surgery](https://en.wikipedia.org/wiki/Shotgun_surgery): Developer adds features to an application codebase that span a multiplicity of implementors or implementations in a single change
- [Soft code](https://en.wikipedia.org/wiki/Softcoding): Storing business logic in configuration files rather than source code[11]
- [Spaghetti code](https://en.wikipedia.org/wiki/Spaghetti_code): Programs whose structure is barely comprehensible, especially because of misuse of code structures

### Methodological

- [Copy and paste programming](https://en.wikipedia.org/wiki/Copy-and-paste_programming): Copying (and modifying) existing code rather than creating generic solutions
- [Golden hammer](https://en.wikipedia.org/wiki/Law_of_the_instrument): Assuming that a favorite solution is universally applicable (See: Silver bullet)
- [Invented here](https://en.wikipedia.org/wiki/Invented_here): The tendency towards dismissing any innovation or less than trivial solution originating from inside the organization, usually because of lack of confidence in the staff
- [Not invented here (NIH) syndrome](https://en.wikipedia.org/wiki/Not_invented_here#In_computing): The tendency towards reinventing the wheel (failing to adopt an existing, adequate solution)
- [Premature optimization](https://en.wikipedia.org/wiki/Program_optimization#When_to_optimize): Coding early-on for perceived efficiency, sacrificing good design, maintainability, and sometimes even real-world efficiency
- [Programming by permutation (or "programming by accident", or "programming by coincidence")](https://en.wikipedia.org/wiki/Programming_by_permutation): Trying to approach a solution by successively modifying the code to see if it works
- [Reinventing the square wheel](https://en.wikipedia.org/wiki/Reinventing_the_wheel#Related_phrases): Failing to adopt an existing solution and instead adopting a custom solution that performs much worse than the existing one
- [Silver bullet](https://en.wikipedia.org/wiki/No_Silver_Bullet): Assuming that a favorite technical solution can solve a larger process or problem
- [Tester-driven development](https://en.wikipedia.org/wiki/Tester-driven_development): Software projects in which new requirements are specified in bug reports

### Configuration management

- [Dependency hell](https://en.wikipedia.org/wiki/Dependency_hell): Problems with versions of required products
- [DLL hell](https://en.wikipedia.org/wiki/DLL_Hell): Inadequate management of dynamic-link libraries (DLLs), specifically on Microsoft Windows
- [Extension conflict](https://en.wikipedia.org/wiki/Extension_conflict): Problems with different extensions to classic Mac OS attempting to patch the same parts of the operating system
- [JAR hell](https://en.wikipedia.org/wiki/Java_Classloader#JAR_hell): Overutilization of multiple JAR files, usually causing versioning and location problems because of misunderstanding of the Java class loading model
