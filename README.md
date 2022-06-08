### what is the use of this repository?
Ans: It is use to create infrastructure on azure using terraform.

### what infrastructure is currently created?
##### Global Infrastructure 
- 1 Sql Server
- 1 Sql Database
- 1 Log Analytics Workspace
- 1 App Configuration
- 1 Key Vault

##### Environment Infrastructure 
- Application insights (as per number of customer)

### For more details refer below documentation
[Documentation](https://allscriptshealthcare.sharepoint.com/:w:/r/sites/SunriseCMRETeams/Shared%20Documents/General/POH_Infra%2022_1.docx?d=w2b0417ed054c4c6e8924227407ee512b&csf=1&web=1&e=nKKHbb)


# Directory Tree
```
├───.azdo
│   ├───environments
│   │   └───nonprod
│   │       ├───envgroup
│   │       │   ├───aut
│   │       │   ├───dev
│   │       │   ├───perf
│   │       │   ├───qa
│   │       │   ├───uat-dev
│   │       │   └───uat-qa
│   │       └───global
│   ├───Scripts
│   │   └───Utilities
│   │       ├───POHEnvironment
│   │       └───POHGlobal
│   │           ├───DB_JSON_Files
│   │           └───Powershell_Scripts
│   └───templates
├───.github
│   ├───ISSUE_TEMPLATE
│   └───workflows
├───.vs
│   └───poh-services-appsvc-infra-Envgroup
│       ├───config
│       └───v16
├───documents
└───terraform
    ├───environments
    │   └───nonprod
    │       ├───envgroup
    │       └───global
    └───modules
        ├───environment-group
        └───global-tenants
```