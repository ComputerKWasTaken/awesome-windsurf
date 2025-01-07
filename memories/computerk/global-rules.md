<sections>
	<section id="general_principles">
		<title>General Coding Principles</title>
		<description>
            Your overarching goal is to produce code that is clean, efficient, and maintainable. 
            You should always strive for readability, simplicity, and modularity, regardless of the programming language or context. 
            Provide solutions in a supportive manner, ensuring that your recommendations are both actionable and adaptable. 
            Avoid unnecessary complexity: keep your code open to iteration and future growth while preserving its clarity. 
            Building upon these guiding principles, remember to respect language idioms, choose intuitive naming conventions, 
            and consider best practices for error handling and testing from the outset. 
            Whenever possible, aim for solutions that balance clarity with performance, factoring in future scalability and maintainability.
        </description>
		<item>
			<rule>Respect Language Idioms</rule>
			<description>
                Embrace the typical patterns and practices of the language you are using to enhance clarity and consistency. 
                This improves maintainability and aligns with community standards.
            </description>
		</item>
		<item>
			<rule>Write for Humans First</rule>
			<description>
                Code should be understandable at a glance, making it more approachable for collaborators and your future self. 
                Avoid obfuscation or over-optimization that sacrifices readability.
            </description>
		</item>
		<item>
			<rule>Future-Proof Your Design</rule>
			<description>
                Plan for growth and changing requirements, but do not overengineer. Keep your design flexible enough to adapt 
                without complicating the initial implementation.
            </description>
		</item>
	</section>
	<section id="code_quality">
		<title>Code Quality and Readability</title>
		<item>
			<rule>Clarity First</rule>
			<description>Write straightforward code that conveys its intent clearly. Minimize abstraction layers that obscure readability.</description>
		</item>
		<item>
			<rule>Descriptive Naming</rule>
			<description>Use meaningful, consistent names for variables, functions, classes, and modules that reflect their purpose.</description>
		</item>
		<item>
			<rule>Consistent Formatting</rule>
			<description>Follow established style guides and use automated tools to maintain uniform formatting across the codebase.</description>
		</item>
		<item>
			<rule>Comment Thoughtfully</rule>
			<description>Provide comments or docstrings where necessary, but avoid restating what the code already expresses.</description>
		</item>
	</section>
	<section id="architecture_and_modularity">
		<title>Architecture and Modularity</title>
		<item>
			<rule>Encapsulate Complexity</rule>
			<description>Group related logic into self-contained modules or classes with clear, well-documented interfaces.</description>
		</item>
		<item>
			<rule>Loose Coupling</rule>
			<description>Design components to function independently, using abstraction layers or interfaces to reduce interdependencies.</description>
		</item>
		<item>
			<rule>Apply DRY</rule>
			<description>Refactor repetitive or duplicated code into shared utilities or functions to promote reuse and reduce bloat.</description>
		</item>
		<item>
			<rule>Design for Extensibility</rule>
			<description>Structure your codebase so you can add new features and functionalities without requiring major rewrites.</description>
		</item>
	</section>
	<section id="error_handling_and_testing">
		<title>Error Handling and Testing</title>
		<item>
			<rule>Error Awareness</rule>
			<description>Implement robust error handling with clear messages and safe fallback paths for smoother recoveries.</description>
		</item>
		<item>
			<rule>Write Tests Early</rule>
			<description>Create relevant tests at the outset of development to quickly capture edge cases and catch regressions.</description>
		</item>
		<item>
			<rule>Iterative Validation</rule>
			<description>Run your tests frequently to ensure ongoing stability and to identify potential issues as your code evolves.</description>
		</item>
		<item>
			<rule>Proactive Debugging</rule>
			<description>Leverage logging, tracing, and profiling to diagnose and resolve errors efficiently.</description>
		</item>
	</section>
	<section id="performance_and_resource_management">
		<title>Performance and Resource Management</title>
		<item>
			<rule>Choose Efficient Solutions</rule>
			<description>Adopt algorithms and data structures that suit your problem domain, optimizing for efficiency and scalability.</description>
		</item>
		<item>
			<rule>Optimize When Necessary</rule>
			<description>Maintain clarity in your codebase; address performance bottlenecks only after conducting proper profiling.</description>
		</item>
		<item>
			<rule>Manage Resources Properly</rule>
			<description>Follow best practices for handling external resources. For example, use 
				<code>with</code> statements where applicable.
			</description>
		</item>
	</section>
</sections>
