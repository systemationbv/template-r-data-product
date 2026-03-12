<img src="img/favicon.svg"  alt="Rabobank" width="50" height="50"/>

# R Data Product

<br/>

### Prerequisites

A Domain should already exist in order to place the newly created Data Product into it.

<br/>

### Component Basic Information

In the **Data Product details** section, you are expected to provide some basic information related to the Data Product. The description of each field is provided below and after that you will also find an example to better understand what values you can use to create your first Data Product:

<br/>

#### Data Product One Pager
- Name: Name of the Data Product that will be displayed after the creation.
- Domain: Domain in which we want to create the Data Product (Required). In our sandbox environment, you will find the following domains:
    * Finance
    * Marketing
    * Organization
- Identifier: A unique **uneditable** identifier for the entity inside the domain, that will be generated automatically according to the Data Product name provided and the Domain selected. It also contains a number representing the major version of it.
- Development Group: it represents the group of developers with access to the Data Product repositories (Required). A group referring your company name and related to the accounts that we are providing to you should be already created inside the sandbox environment, so you can select it:
    * guest_admin
    * guest_developer
    * guest_user
- Data Product Owner: The user who owns the particular Data Product (Required).
- Contact email: Point of contact, it could be the owner or a distribution list (Required).
- Data Product Type: Select one of the following types (Required)
    * Source Aligned
    * Consumer Aligned
    * Domain Agnostic

<br/>

_Example:_

| Field name             | Example value                       |
|:-----------------------|:------------------------------------|
| **Name**               | DPAT_QuarterlyData                  |
| **Domain**             | domain:Finance                      |
| **_Identifier_**       | _finance.dpat_quarterlydata.0_      |
| **Development Group**  | group:datameshplatform              |
| **Data Product Owner** | owner:guest_developer               |
| **Contact Email**      | joe.smith@mycompany.com             |
| **Data Product Type**  | Data Product Type: Source Aligned   |

<br/>

#### Data Product Concept
Give a short explanation about the following items:
   * Which are the main Data Product components? (Required)
   * What is the scope of the Data Product? (Required)
   * What new characteristics does this Data Product create? (Required)

<br/>

#### Business Value
Give a short explanation about the following items:
   * Which business value is this Data Product generating? (Required)
   * Which use cases is it serving? (Required)

<br/>

#### Consumers
Give a short explanation about the following items:
- Who are the current consumers? Multiple selection item.(Required)
   * Name
   * Marketing
   * Finance
   * Organization
- Who are (potential) target consumers? (Required)
   
<br/>

#### Dependencies
Add a depencies risk (if needed) and give a short description of it/them.
   * Dependencies Risks
 
<br/>

#### Data Product Details
Select a System Owner:
   * guest_admin
   * guest_developer
   * guest_user

 
<br/>

#### Review and Create
After the final step the system will show you the summary of the template, and you can go back and edit or go ahead and create the Component. With the examples values given here it should look something like this:


_Example:_

| Field name                                                 | Example value                       |
|:-----------------------------------------------------------|:------------------------------------------------------|
| **Name**                                                   | DPAT_QuarterlyData                                    |
| **Domain Type Ref**                                        | domaintype:default/business-domain                    |
| **Domain**                                                 | domain:finance                                        |
| **Domain Name**                                            | Finance                                               |
| **Identifier**                                             | finance.dpat_quarterlydata.0                          |
| **Development Group**                                      | Rabobank development                                  |
| **Data Product Owner**                                     | user:guest_developer                                  |
| **Contact Email**                                          | witboost@rabobank.com                                 |
| **Data Product Type**                                      | Source Aligned                                        |
| **Which Are The Main Data Product Components**             | financial records                                     |
| **What Is The Scope Of Data Product**                      | Business intelligence                                 |
| **What New Characteristics Does This Data Product Create** | Not available                                         |
| **Which Business Value Is This Data Product Generating**   | To be seen                                            |
| **Which Use Cases Is It Serving**                          | Automatation of generation of quarterly documents     |
| **Who Are The Current Consumers**                          | domain:marketing, domain:finance, domain:organization |
| **Who Are Potential Target Consumers**                     | domain:marketing, domain:finance, domain:organization |
| **Dependencies Risks**                                     | None                                                  |
| **System Owner**                                           | user:guest_developer                                  |

<br/>

#### Create
After clicking on "Create" the registration of the Data product will start. If no errors occurred it will go through the 3 phases (Fetching, Publishing and Registering) and will give you the links to the newly created Repository and the data product page in the Builder.


#### Users guide
Click [here](https://github.com/systemationbv/template-r-data-product/tree/main/docs/docs/r-data-product-users-guide.pdf) for the graphical users guide
