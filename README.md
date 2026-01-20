# Erg Snippets for VS Code

**Enhance your development experience with versatile snippets for React, Vue, Angular, Next and more!**

The **erg-snippets** extension for Visual Studio Code offers a comprehensive collection of snippets for JavaScript, TypeScript, and various popular frameworks. Whether you're working with React, Vue, Angular, or Next.js, this extension streamlines your workflow by providing quick access to commonly used component structures and patterns. **All snippets come with built-in styling - no external CSS frameworks required!**

![Use Extension With Angular](https://raw.githubusercontent.com/Furkan-Erg/erg-snippets/refs/heads/master/raw/main/images/angular.gif)
![Use Extension With Next/React](https://raw.githubusercontent.com/Furkan-Erg/erg-snippets/refs/heads/master/raw/main/images/react.gif)
![Use Extension With Vue](https://raw.githubusercontent.com/Furkan-Erg/erg-snippets/refs/heads/master/raw/main/images/vue.gif)

## Features

- **Zero Dependencies**: All snippets use inline styles or scoped CSS - no Tailwind, Bootstrap, or other CSS frameworks required
- **Framework Agnostic Styling**: Works out of the box with any project setup
- **TypeScript Support**: Full TypeScript support for React (TSX) and Vue components
- **Modern Design**: Clean, professional UI components with hover effects and transitions
- **20+ Components**: Comprehensive collection of commonly used UI components

## Supported Frameworks

- React (JSX and TSX)
- Vue
- Angular
- Next.js
- And more...

## Usage

Type part of a snippet, press `Enter`, and watch it unfold into your code.

Alternatively, you can press `Ctrl` + `Space` (Windows, Linux) or `Cmd` + `Space` (macOS) to activate snippets from within the editor.

## Available Snippets

### Pages

| Snippet        | Purpose                              |
| -------------- | ------------------------------------ |
| `erg-login`    | Login page with form validation      |
| `erg-register` | Registration page with validation    |
| `erg-404`      | 404 Not Found page with navigation   |
| `erg-about`    | About Us page with team section      |

### UI Components

| Snippet             | Purpose                                         |
| ------------------- | ----------------------------------------------- |
| `erg-button`        | Button with variants (primary, danger, etc.)    |
| `erg-card`          | Card component with image and footer support    |
| `erg-modal`         | Modal dialog with customizable footer           |
| `erg-navbar`        | Responsive navbar with mobile menu              |
| `erg-footer`        | Footer with multiple link sections              |
| `erg-alert`         | Dismissible alert (info, success, warning, error) |
| `erg-spinner`       | Loading spinner with customizable size          |
| `erg-badge`         | Badge/tag with color variants                   |
| `erg-avatar`        | Avatar with initials fallback and status        |

### Data & Forms

| Snippet             | Purpose                                         |
| ------------------- | ----------------------------------------------- |
| `erg-table`         | Sortable data table                             |
| `erg-search`        | Search input with clear button                  |
| `erg-search-select` | Searchable dropdown with keyboard navigation   |
| `erg-tabs`          | Tab navigation component                        |
| `erg-pagination`    | Pagination with ellipsis                        |
| `erg-accordion`     | Collapsible accordion sections                  |
| `erg-toast`         | Toast notification system with context          |

## Component Examples

### Button Variants

```jsx
<Button text="Primary" variant="primary" />
<Button text="Danger" variant="danger" />
<Button text="Success" variant="success" size="large" />
<Button text="Outline" variant="outline" />
```

### Card with Image

```jsx
<Card
  title="Card Title"
  description="Card description goes here"
  image="https://via.placeholder.com/400x200"
  hoverable
  footer={<button>Learn More</button>}
/>
```

### Table with Sorting

```jsx
const columns = [
  { key: 'name', label: 'Name' },
  { key: 'email', label: 'Email' },
  { key: 'status', label: 'Status' },
];

const data = [
  { name: 'John', email: 'john@example.com', status: 'Active' },
];

<Table columns={columns} data={data} sortable />
```

### Toast Notifications

```jsx
// Wrap your app with ToastProvider
<ToastProvider>
  <App />
</ToastProvider>

// Use the hook in any component
const { addToast } = useToast();
addToast('Success!', 'success');
```

## Installation

1. Install Visual Studio Code 1.10.0 or higher.
2. Launch Visual Studio Code.
3. Open the command palette by pressing `Ctrl` + `Shift` + `P` (Windows, Linux) or `Cmd` + `Shift` + `P` (macOS).
4. Select `Install Extension`.
5. Search for **erg-snippets** and click install.
6. Reload Visual Studio Code to activate the extension.

## Styling Approach

Each framework uses the most appropriate styling method:

- **React (JSX/TSX)**: Inline styles with JavaScript objects
- **Vue**: Scoped CSS in `<style scoped>` blocks
- **Angular**: Component-level styles in the `styles` array

This ensures your components work immediately without any additional configuration or dependencies.

## Customization

All snippets include placeholder values (marked with `${1:...}`) that you can quickly tab through and customize:

- API endpoints
- Company names
- Team member names
- Default text content

## Contribution

We welcome contributions to enhance the functionality and usability of this extension. If you have suggestions or improvements, feel free to submit a pull request or open an issue.

### Ideas for New Snippets

- Sidebar navigation
- Dropdown menu
- Tooltip component
- Progress bar
- File upload
- Date picker

## Credits

Thanks to everyone who contributed to making **erg-snippets** a reality!

- Developed by [Furkan Ergüldürenler](https://github.com/Furkan-Erg)

---

**Happy coding!**
