EduPulse - Comprehensive School Management System
EduPulse is a modern, high-performance, and responsive School Management Dashboard designed to streamline academic operations. Built with a focus on component-driven architecture and strict type safety, it provides seamless data tracking and user experience for administrators, teachers, students, and parents.

🚀 Live Demo
You can view the live deployment of the project here: https://your-project-link.vercel.app

✨ Key Features
Role-Based Views: Tailored dashboards and features optimized for Administrators, Teachers, Students, and Parents.

Dynamic Form Management: Centralized global modal system managing complex dynamic forms efficiently.

Academic Schedule Integration: Full-featured, interactive custom academic calendar tracking classes and exams.

Data Analytics & Visualization: Interactive visual charts tracking school performance, attendance, and financial metrics.

Advanced Data Tables: Highly optimized data grids featuring client-side searching, advanced filtering, and pagination.

Responsive Layout: Mobile-first responsive UI built for flawless performance across mobile, tablet, and desktop devices.

🛠️ Tech Stack & Architecture
Framework: Next.js (App Router, Server-Side Rendering)

Language: TypeScript (Strict type safety and robust interface definitions)

Styling: Tailwind CSS (Component-driven design, arbitrary variants for high-fidelity UI layout)

Form Management: React Hook Form

Data Validation: Zod (Schema-based runtime validation)

Visualizations: Recharts / Chart.js

📦 Installation & Getting Started
Follow these steps to run the development environment locally:

Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Install dependencies:
npm install

Run the development server:
npm run dev

Open your browser:
Navigate to http://localhost:3000 to see the application in action.

🎯 Challenges Faced & Learning Outcomes
Dynamic Modal Architecture: Designed a highly reusable FormModal system that dynamically handles multiple actions (create, update, delete) across 10+ distinct database tables, cutting redundant code significantly.

Responsive Data Density: Solved the UX challenge of displaying high-density tabular data on mobile screens using strategic Tailwind CSS display breakpoints (md:hidden, lg:table-cell).

Data Integrity: Implemented strict schema validation using Zod alongside custom TypeScript interfaces (InputFieldProps) to prevent structural runtime errors.

📝 License
This project is open-source and available under the MIT License.
