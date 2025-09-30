# Laptop Request Catalog Item

## Project Overview

**Category:** ServiceNow System Administrator  
**Skills Required:** Service Catalog, UI Policies, UI Actions

This project develops a dynamic Service Catalog item in ServiceNow for employees to request laptops efficiently. The solution automates and streamlines the workflow, replacing the current manual process that is slow and error-prone.

### Key Features
- Dynamic form fields with UI Policies
- Form reset capability using UI Actions
- Clear instructions for users to minimize errors
- Tracking all changes for governance and deployment
- User-friendly interface leveraging ServiceNow's Service Catalog capabilities

## Objectives

- ✅ Provide employees with a user-friendly interface to request laptops
- ✅ Implement dynamic form behavior using UI Policies
- ✅ Include UI Actions for additional functionalities like resetting the form
- ✅ Ensure proper tracking of catalog item changes
- ✅ Test and validate the catalog item to ensure it works as intended

## Implementation Steps

### Step 1: Create Local Update Set
Create a local update set to capture all project changes for deployment or migration to other instances.

### Step 2: Create Service Catalog Item
- Navigate to **Service Catalog → Maintain Items**
- Create a new catalog item named **"Laptop Request"**
- Set Category, Name, and Description appropriately

### Step 3: Add Variables
Add variables to capture user input:
- Employee Name
- Department
- Laptop Model
- Required Specifications
- Justification/Comments

### Step 4: Create Catalog UI Policies
Implement UI Policies to dynamically show/hide fields, make fields mandatory, or enforce conditions based on user input.

**Examples:**
- Make "Laptop Model" mandatory if "Department" is selected
- Show additional specifications if "High Performance Laptop" is selected

### Step 5: Create UI Action
- Add a UI Action for resetting the form
- Allows users to clear all entered data and start fresh without refreshing the page

### Step 6: Export Changes
Export the Update Set to another ServiceNow instance for testing or deployment.

### Step 7: Retrieve Update Set
In the target instance, retrieve the update set and commit changes to apply the catalog item and associated policies.

### Step 8: Test Catalog Item
- Access the Service Catalog as an end user
- Verify dynamic behaviors, mandatory fields, and reset functionality
- Ensure all entries are captured correctly in the backend

## Testing Checklist

- [ ] Catalog item visible in Service Catalog
- [ ] Fields dynamically appear/disappear according to UI Policies
- [ ] Mandatory fields enforced correctly
- [ ] UI Action for reset works properly
- [ ] Requests created correctly in the backend
- [ ] Update Set changes successfully applied in another instance

## Project Screenshots

The following screenshots document the implementation process:

1. **Create an Instance.png** - Initial instance setup
2. **Service Catalog.png** - Service Catalog overview
3. **Catalog Hardware Section.png** - Hardware category configuration
4. **New Laptop Request.png** - Basic laptop request form
5. **Laptop Request with Extra Items.png** - Enhanced form with additional options
6. **Check Out & Order.png** - Final checkout and order process

## Conclusion

The Laptop Request Catalog Item project successfully streamlines the laptop request process in the organization. By implementing a dynamic Service Catalog item, employees now have an intuitive and user-friendly interface, reducing errors and improving efficiency.

This project demonstrates how ServiceNow can replace manual, error-prone processes with automated, efficient, and user-centric solutions. It enhances service delivery, ensures governance, and improves employee satisfaction by providing a modern request experience.

### Benefits Achieved
- **Improved Efficiency:** Automated workflow reduces processing time
- **Better User Experience:** Intuitive interface with dynamic form behavior
- **Error Reduction:** UI Policies enforce data validation and mandatory fields
- **Enhanced Governance:** Update sets ensure proper change tracking
- **Scalability:** Solution can be easily deployed across multiple instances

---

**Project Status:** ✅ Completed  
**Documentation Date:** September 30, 2025  
**Author:** ServiceNow System Administrator
