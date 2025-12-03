# jupyterhub-contrib org
The [jupyterhub-contrib](https://github.com/jupyterhub-contrib) GitHub organisation is a centralised space for community members to collaborate on JupyterHub-adjacent projects in a welcoming and organizationally neutral way.

If you are contributing to any of the repos in `jupyterhub-contrib`, you are a JupyterHub contributor! 
While membership in any project under  is not required to call oneself a "JupyterHub contributor", if you do have membership, you definitely are a JupyterHub contributor! Congratulations :) 

::: important
The repos in the `jupyerhub-contrib` organisation are not actively maintained by the core JupyterHub team. 
Some project members members might contribute to individual repos in a personal capacity, but this is on a case-by-case basis. 
:::



(jhcontrib-criteria-social-checklist)=
## Criteria for inclusion: Social
The primary goal for the social criteria is to ensure that projects in `jupyterhub contrib` are vendor neutral (in terms of who has control) as well as actively, broadly useful.
- [ ] Evidence of active collaboration: at least two active contributors who are not from the same organization (broadly defined).
- [ ] Evidence of use by two different groups, as broadly defined. This may just be 'intent to use' for early stage projects.
- [ ] Clearly documented security response process, with a prominent notice that security patches for this project are not handled by the JupyterHub core team
- [ ] Application of the Jupyter Code of Conduct, with all contributors subject to it

**Evidence of active collaboration**
This is not exclusively about code contribution, but about establishing that this project is not exclusively controlled by one vendor or institution.
_If a project originates in one organization, it should seek contributors from a different organization before it can be accepted to `jupyterhub-contrib`._

**Clearly documented security response process**
 It's ok to say that there's no guarantee of a security response, but this must be still explicitly stated.

The Jupyter CoC applies, and all contributors will be subject to it in exactly the same way they would be under the jupyterhub/ GH org. 
The initial (minimum 2) contributors will be granted 'admin' rights on the repo, and and listed on the README. They may invite whoever they wish to the project and manage rights as they see fit. Ideally, as new users get granted rights, they will be mentioned in the README for better visibility.
JupyterHub core team members do automatically get rights (by dint of having rights over the whole org), but there are no expectations on them maintaining any of these projects. This lack of commitment shall be prominently displayed in the README alongside current list of actual maintainers. JupyterHub core team members may also be contributors to these projects, but that's done in their individual capacity and does not commit the entire core team to the project.

(jhcontrib-criteria-tech-criteria)=
## Criteria for inclusion: Technical 

- [ ] Uses a `pre-commit.ci` based pre-commit file for ensuring autoformatted code styling and linting. 
- [ ] Has an established release process that any contributor can follow to make releases, present as a RELEASE.md file or as a section in the README.md.
Has an established process to get someone set up to contribute to the project, present as a CONTRIBUTING.md file or as a section in the README.md.
Licensing matches that of the JupyterHub projects:
Licensed under 3-BSD (although an additional OSI approved license is acceptable, if this project is at the intersection of two communities that have differing licensing needs)
Copyright notice, when required, is set to 'Project Jupyter Contributors'
There is no copyright assignment of any sort - individuals retain copyright to their own contributions. This means no Contributor License Agreements or similar may be required to contribute to this project.
Documentation is published via Read The Docs. If there are technical challenges preventing this, GitHub pages is also acceptable.
- [ ] For Python based projects, PyPI Trusted Publisher mechanism must be used to avoid relying on specific individuals' PyPI accounts.
- 


This helps keep everyone on the same page and avoids long conversations about code style. (Editors's note: We can ideally just link to a specific file here and require everyone use that.)
