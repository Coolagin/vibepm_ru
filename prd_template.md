# vibepm - Vibe Product Management

PRD Template Example:

```markdown
# Product Requirements Document: [Project Name]

## 1. Project Overview

- Clear, concise statement of the project's purpose
- Target users and their primary needs
- Key business objectives and success metrics

### 1.1 Purpose

[One-paragraph description of what this project is and why it matters]

### 1.2 Target Users

- Primary: [Description of main user persona]
- Secondary: [Description of secondary user personas]

### 1.3 Business Objectives

1. [Objective 1]
2. [Objective 2]
3. [Objective 3]

### 1.4 Success Metrics

- [Metric 1]: [Target value]
- [Metric 2]: [Target value]

## 2. Functional Requirements

- Detailed feature descriptions organized by priority
- User stories in a consistent format ("As a [user], I want to [action] so that [benefit]")
- Acceptance criteria for each feature

### 2.1 Core Features

#### 2.1.1 [Feature Name] - PRIORITY: HIGH

**Description**: [Clear description of what this feature does]

**User Stories**:
- As a [user type], I want to [action] so that [benefit].
- As a [user type], I want to [action] so that [benefit].

**Acceptance Criteria**:

- [ ] [Criterion 1]
- [ ] [Criterion 2]
- [ ] [Criterion 3]

#### 2.1.2 [Feature Name] - PRIORITY: MEDIUM

...

### 2.2 Secondary Features

...

## 3. Technical Requirements

- Architecture preferences and constraints
- API integrations needed
- Performance requirements
- Security and compliance needs

### 3.1 Architecture

- [High-level architecture description]
- [Diagram or reference to architectural document]

### 3.2 API Integrations

1. [API Name]
   - Endpoints needed: [list]
   - Authentication method: [method]
   - Rate limits: [if applicable]

### 3.3 Performance Requirements

- Page load time: [target]
- API response time: [target]
- Concurrent users: [target]

### 3.4 Security & Compliance

- [Security requirement 1]
- [Security requirement 2]
- Compliance with: [standards/regulations]

## 4. UI/UX Requirements

- User flow diagrams
- Wireframes or mockups (references to design files)
- Design system or styling guidelines

### 4.1 User Flows

[Description or reference to user flow diagrams]

### 4.2 Wireframes

[References to wireframes or mockups]

### 4.3 Design System

- Color palette: [colors]
- Typography: [fonts]
- Component library: [if applicable]

## 5. Data Requirements

- Data models and relationships
- Storage requirements
- Data processing workflows

### 5.1 Data Models

```javascript
// Example User model
{
  id: string,
  name: string,
  email: string,
  role: enum['admin', 'user', 'guest'],
  createdAt: timestamp
}

### 5.2 Database Requirements

* Type: [SQL/NoSQL/etc.]
* Estimated size: [initial and growth projections]
* Backup requirements: [frequency and retention]

### 5.3 Data Processing Workflows

* [Description of any ETL processes]
* [Description of data analytics requirements]

## 6. Timeline and Milestones

- Development phases
- Dependencies between components

### 6.1 Development Phases

1. **Phase 1** (Weeks 1-3)
   * [Feature 1]
   * [Feature 2]
2. **Phase 2** (Weeks 4-6)
   * [Feature 3]
   * [Feature 4]

### 6.2 Dependencies between components

* [Feature A] must be completed before [Feature B]
* [External dependency] is required for [Feature C]

---

## 7. Implementation Notes for AI Tools

### 7.1 Recommended Technologies

* Frontend: [frameworks/libraries]
* Backend: [frameworks/libraries]
* Testing: [frameworks/approaches]

### 7.2 Code Organization

* [Preferred patterns]
* [Module organization]
* [Naming conventions]

### 7.3 Testing Strategy

* Unit test coverage target: [percentage]
* Integration testing approach: [description]
* End-to-end testing requirements: [description]
```
