# User Stories and Tasks — Book Swap SA

**Module:** PRP372S — Project Presentation 3  
**Project:** Book Swap SA — Second-Hand Textbook Swap

## 1. Introduction

User stories describe the features of Book Swap SA from the perspective of the people who will use the system. They help the team understand user needs and break larger features into smaller tasks that can be planned and developed.

The following stories describe proposed functionality for the textbook-swapping platform. Their implementation status should be confirmed against the actual project.

## 2. User Stories

### User Story 1: Search for Textbooks

**User story:**  
As a student, I want to search for textbooks by title so that I can find the textbook I need.

**Acceptance criteria:**
- The user can enter a textbook title into the search field.
- The system displays matching textbooks when available.
- The system provides an appropriate message when no matching textbooks are found.

**Tasks:**
1. Create a search field.
2. Define how textbook records will be searched.
3. Display matching results.
4. Test searches with matching and non-matching titles.

### User Story 2: Filter Textbooks

**User story:**  
As a student, I want to filter textbook listings so that I can narrow down the available options.

**Acceptance criteria:**
- The user can select an available filter.
- The displayed results reflect the selected filter.
- The user can clear the filter to view the broader list again.

**Tasks:**
1. Identify suitable filters for the project.
2. Create the filter controls.
3. Apply the selected filters to textbook listings.
4. Test the filtering functionality.

### User Story 3: List a Second-Hand Textbook

**User story:**  
As a student, I want to list a textbook I no longer need so that another student can discover it.

**Acceptance criteria:**
- The user can enter the required textbook details.
- Required fields are validated.
- A valid listing can be submitted and displayed if listing functionality is supported.

**Tasks:**
1. Identify the required textbook fields.
2. Create the listing form.
3. Validate the form input.
4. Test valid and invalid submissions.

### User Story 4: View Textbook Details

**User story:**  
As a student, I want to view a textbook's details so that I can decide whether it meets my needs.

**Acceptance criteria:**
- A textbook listing displays its available details.
- The details include relevant information such as title, author and condition when provided.
- The user can return to the textbook listings.

**Tasks:**
1. Define the textbook information to display.
2. Create a textbook details view.
3. Connect listings to their details.
4. Test the navigation and displayed information.

### User Story 5: Use the Website on Different Devices

**User story:**  
As a student, I want to use Book Swap SA on a phone or computer so that I can access the platform on my preferred device.

**Acceptance criteria:**
- The page adjusts to different screen sizes.
- Text and controls remain readable.
- Important content remains accessible on smaller screens.

**Tasks:**
1. Apply responsive layout techniques.
2. Test the layout at different screen sizes.
3. Correct any layout or
## 3. Evidence

The user stories and associated tasks in this document provide evidence of the requirements identified for Book Swap SA. Each story describes a need from the student's perspective, while the acceptance criteria explain how the expected functionality can be assessed.

The tasks break the proposed features into smaller activities that can guide development and testing. Supporting evidence can include screenshots of the project's existing Trello board, where relevant user stories and development tasks are recorded.

## 4. Reflection

Developing these user stories helped me understand how to describe software requirements from the user's perspective rather than focusing only on technical implementation. Writing acceptance criteria also helped me recognise the importance of defining what a feature should do before considering it complete.

Breaking each story into smaller tasks provides a clearer way to plan development, share responsibilities and identify work that needs testing. As the Frontend Developer, I can use these requirements to guide the design of interfaces and ensure that the features I work on address the needs of CPUT students.

This exercise also showed me that user stories need to be clear, achievable and testable. In future development, I can improve my approach by collaborating with the team to refine requirements, confirm priorities and check completed features against their acceptance criteria.
