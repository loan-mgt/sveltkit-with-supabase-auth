# SvelteKit with Supabase Auth Template

This is a SvelteKit project template with Supabase authentication integration. It provides a starting point for building web applications with user authentication using Supabase.

For more detailed instructions, you can refer to the official [Supabase guide](https://supabase.com/docs/guides/getting-started/tutorials/with-sveltekit) on integrating Supabase with SvelteKit.

## Getting Started

Follow these steps to get your project up and running:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/sveltekit-supabase-auth-template.git
cd sveltekit-supabase-auth-template
```

### 2. Create a Supabase Project

Before proceeding, make sure you have a Supabase project set up. If you haven't, go to [Supabase](https://supabase.io/) and create a project.

### 3. Create an Environment File

Create a `.env` file in the root of your project directory and add the following environment variables:

```env
PUBLIC_SUPABASE_URL="YOUR_SUPABASE_PROJECT_URL"
PUBLIC_SUPABASE_ANON_KEY="YOUR_SUPABASE_ANON_KEY"
```

Replace `YOUR_SUPABASE_PROJECT_URL` and `YOUR_SUPABASE_ANON_KEY` with the actual values from your Supabase project.

### 4. Install Dependencies

Install the project dependencies using npm:

```bash
npm install
```

### 5. Run the Development Server

Start the development server to run your SvelteKit application:

```bash
npm run dev
```

Your SvelteKit project with Supabase authentication is now up and running. You can start building your application with user authentication!

## Have Fun Coding! 🚀

Don't forget to add some emojis to your code for fun! 😄

Happy coding and enjoy using this template for your SvelteKit and Supabase project!
