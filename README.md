>Spring:

	Advantages :
	1) Predefined Templates
	2) Loose Coupling
	3) Easy to test
	4) Lightweight
	5) fast Development
	6) Powerful abstractipn
	7) Declarative Support (Cachin, Validation, Transaction and formating)


>Spring Modules:

	-Test
		>Test module
	-Spring Core Container
		>Core module
		>Bean module
		>Contest module
		>Expression Language module
			(Core and Bean Module provide IOC and DI features)


		>AOP module
		>Aspect module
		>Instrumentation module
	-Data Access/ Integration
		>JDBc module
		>ORM module
		>OXM moduel
		>JMS modules
		>Transaction modules
			(This modules Provied support to interact with Database)
	-Web
		>web module
		>servlet module
		>Struts module
		>Protlet module
			(this module provied support to create web application)


>IOC Container
	- responsible to instantiate application class, configure and assemble the objects.
	- to configure the object
	- to assemble the dependencies between the object

	two types of IOc containers
		1) Bean Factory
		2) ApplicationContext
	applicationContext interface is build on the top of the BeanFactory interface

		-XmlBeanFactory is implementation class for Beanfactory interface.
		-ClassPathCmlAppliactionContext is implementation class of AppliactationContext
		

