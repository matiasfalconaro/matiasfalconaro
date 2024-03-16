```Python
resume_highligths = {
    "profile": Profile(
        name="Matias Falconaro",
        role="Software Developer",
        specialization=Specialization(
            focus="Cloud Back-End Solutions",
            areas=["Development", "Cloud Computing", "DevOps"]
        )
    ),
    "contact": Contact(
        email="matiasfalconaro@gmail.com",
        links=Links(linkedIn="https://linkedin.com/in/matiasfalconaro")
    ),
    "skills": [
        Skill(name="Sys Admin", technologies=["Linux", "Bash Scripting", "Pipelining"]),
        Skill(name="Database", technologies=["PostgreSQL", "SQLite3", "SAP HANA"]),
        Skill(name="Cloud", technologies=["AWS", "SAP BTP", "Docker", "CloudFoundry"]),
        Skill(name="Core", technologies={
          "Front-End": ["HTML", "CSS", "JavaScript", "React"],
          "Back-End": ["Python", "SQLAlchemy", "Flask"]
        }),
    ]
}
```
