This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Steps to Set Up the Web App

1. **Create a Repository**
   - Create a new repository in your version control system (e.g., GitHub, GitLab).
   - Upload the `.ttl` files to the **import** directory within the repository.

2. **Configure the Backend**
   - Copy the link to the repository.
   - Update the `server.js` file:
     - Set the `GRAPHDB_ENDPOINT` variable to the link of the repository.
     - Use the `PORT` variable to specify the port where the server will run.

3. **Update Frontend Files**
   - Modify the server link in the following frontend files to point to the correct backend endpoint:
     - `SearchBar.tsx`
     - `FoodList.tsx`
     - `add-calories/page.tsx`

4. **Run Development Server**
   - Open a terminal and execute the following commands:
     ```bash
     npm run dev
     node server.js
     ```

5. **Launch the Application**
   - Once the above commands run successfully, the **Calorie Tracker** web application will be up and running.

## Getting Started

First, run the development server:

```bash
git clone https://github.com/DeepanjayNandal/Nutritional-Calculator-Web-App.git
cd Nutritional-Calculator-Web-App
npm install
npm run dev
```

## Usage

- Enter an ingredient (e.g., "butter").
- View its nutritional profile.
- See alternative suggestions like "olive oil" with improved macros.

## Security

- No user data is stored.
- All queries are sanitized to prevent injection attacks.

## Future Improvements

- Add user accounts and dietary profiles.
- Expand to meal-based suggestions.
- Support barcode scanning for ingredients.
