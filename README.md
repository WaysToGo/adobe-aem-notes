# adobe-aem-notes

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





