# Adobe-AEM-Notes

what is AEM?

which is a enterprise web content managment system

---

why AEM?

 - You can build and manage mobile sites and responsive designs from one single platform
 - Develop unlimited and customized variations of assets including format, size, color and zoom, by working with only one set of assets
 - Your assets can be accessed and managed from the cloud
 - Using a single code base, you can build mobile apps and deliver them to multiple platforms.
 - Develop automated workflows, and merge form data and documents with your existing systems

:point_right::mag_right:[reference](https://blog.3sharecorp.com/why-adobe-experience-manager-aem-for-your-web-content-management-system)

---


Infrastructure
- infrastructure level AEM has web-application server
- standalone mode uses integrated server jetty-web-server
- web application where it uses third party server
- web application framework (sling)->which simplify the rest content oriented applications
- Content repository (JCR)->database for structured and semi structured data

---

Granate
- granate is open development but not open source
- AEM is build up on granate
- application launcher
- OSGI Framework where bundling is done
- provides logging services

---

OSGI Framework
- modular
- titly coupled and dynamicaly loadable classes

---

Felix
- open source implementation of OSGI speification
- dynamic run time environment

---

JCR(Java Content Repository)
- database supports structured and unstructured data
- html css javascript images.. are stored in JCR object database
- name spaces example(jsr:title)

---

Apache Sling
- based on Rest principle
- sling every thing is a resource
-

---

namespaces

- **jcr:** for basic data storage
- **nt:** foundation node types  example(nt:file ,nt:folder,nt:unstructured) nt->nodetype
- **rep:** repository internals
- **cq:** common aem name spaces example(cq:Dialog,cq;Page)

---



folder structure
- conf->contains all configurations for site (dynamic content/policy)
- etc->stores content related to utilities and tools
- home->related groups and users

---
notes
- aem is built on database called JCR
- which has two things nodes and properties
- nodes->provides structure in JCR
- properties->store data which has key and value

---

terminology
- sling:resourceType->to search rendering script(html or jsp pages)
- sling:resourceSuperType->
- cq:design_dialog ->is used to show data optionally (one data is added to the component it will reflect in all pages)

---
importent
- templeate allowed path-> ```/content(/.*)?``` which tells it to create page anyplace in content folder
---

links
- http://localhost:4502/libs/granite/ui/content/dumplibs.html (what all are using clientlibs (css and js) )
- to load  page without cq,aem markup remove editor.html and add ``` ?wcmmode=disabled ``` at the end (to view final version)
---

##  Jcr

//path.tidy.infinity.json path, which tells Sling to return a formatted JSON
:point_right::mag_right:[reference](https://dzone.com/articles/java-content-repository-best)

