![Banner](https://capsule-render.vercel.app/api?type=waving&color=0:09203f,100:1d4ed8&height=100&section=header)

# Marco Carricato
 
My journey in computer science started in high school with an IT technician diploma, and I'm now finishing my B.Sc. in Computer Engineering at the University of Florence. Driven by a genuine passion for technology and continuous learning, I plan to start working right after graduation and later pursue a master's degree in Robotics and Automation.

**Open to internships and entry-level roles as a Software Developer or Tech Consultant in product-focused and tech-driven companies.**

[![Connect on LinkedIn](https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=flat)](https://www.linkedin.com/in/marco-carricato-029233451)

<br>

[![My Skills](https://skillicons.dev/icons?i=c,cpp,java,py,js,php,mysql,docker,git)](https://skillicons.dev)

C · C++ · Java · Python · JavaScript · PHP · MySQL · Docker · Git

## What I'm working on now

**Undergraduate thesis**

*Progettazione e sviluppo di un editor interattivo per dataset GTFS: ricalcolo topologico, routing e matrici di coincidenza tramite WebGIS e architettura KM4City su Snap4City*

If a bus stop is moved or a route is detoured, how do arrival times and network connections change along the line?

I am building a WebGIS editor integrated into the Snap4City Smart City platform that turns semantic transit data (KM4City) into an editable GTFS model without altering production records (Copy-on-Write). Using road geometries and orthogonal projection, the tool recomputes cumulative stop distances and reconstructs missing or updated timetables through a multi-regime kinematic model constrained by speed limits and OpenStreetMap bus-lane data.

The editor exports validated, standard 3NF GTFS `.zip` feeds ready for Snap4City's RDF knowledge-base ingestion pipeline. The goal is also to generate transfer coincidence matrices between routes to evaluate which passenger connections are maintained, lost, or gained after a schedule or route modification.

[![Read the](https://img.shields.io/badge/Read%20the-documentation-0A66C2?style=flat)](https://github.com/marcocarri/gtfs-editor-tesi-marcocarricato#readme-ov-file)

## Selected projects

### [Venue Event Organiser](https://github.com/MeruemMeurel/Venue_Event_Organiser)
Venue & Event Organiser is a Java application designed to simplify the management of venues and events. It helps users organize event details, schedules, bookings, and venue availability within a clear, structured interface.
The project demonstrates practical object-oriented design principles, including data management, modular components, and essential validation. It is intended to provide an accessible foundation for coordinating events while keeping information organized and easy to update.
Future development could expand the application with a database, graphical interface, authentication, and reporting features. The project is suitable for showcasing Java development skills and understanding how event-management systems can be structured.

### [Weather Forecast API](https://github.com/marcocarri/carricato_WeatherForecast_API)
A Django REST API for simulated weather forecasts, featuring JWT authentication, IP/user-based daily rate limiting, aggregated query statistics, and role-based moderation (RBAC). The README includes local setup, demo accounts, and a full HTTPie test workflow. [Explore the live Swagger docs](https://marcocarri.eu.pythonanywhere.com/api/docs/)

### [La Repubblica Mockup](https://github.com/marcocarri/carricato_laRepubblica_mockup)
A responsive and accessible (WAVE > 9) React and Bootstrap replica of the *La Repubblica* news homepage. The part I'd point you to is how the header and editorial grid handle scroll and viewport shifts: scroll-threshold hysteresis prevents sticky-header flickering, while a polymorphic `NewsCard` component and off-canvas menu adapt seamlessly across the 768px breakpoint. [Try out the live Demo](https://marcocarri.github.io/carricato_laRepubblica_mockup/)
