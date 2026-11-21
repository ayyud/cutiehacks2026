# Bear Call 

**Every campus alert is a one-way broadcast. Bear Call takes attendance.**

Bear Call is a campus emergency response platform that helps emergency personnel identify students who need assistance and coordinate responders during campus emergencies.

Using real-time location data, student safety check-ins, and interactive 3D campus maps, Bear Call helps dispatchers determine who needs help, where they are, and how responders can reach them.

## How It Works

1. **Emergency Occurs:** An emergency takes place on campus.
2. **Select Affected Zones:** Dispatchers access an interactive 3D campus map and select the areas affected by the emergency.
3. **Locate Students:** Bear Call uses students' shared locations to identify who is near the affected zones.
4. **Send Emergency Alerts:** Students in affected areas receive notifications on their phones.
5. **Student Check-In:** Students answer five short questions about their safety and current situation.
6. **Identify Students in Need:** Bear Call analyzes responses to identify students requiring assistance. Students who do not respond are flagged as potentially needing help.
7. **Assign Responders:** Dispatchers review students needing assistance and approve responder assignments.
8. **3D Responder Navigation:** Responders receive an interactive 3D campus map that guides them directly to students needing help.
9. **Provide Assistance:** Responders receive relevant information about each student's situation before arriving.

## User Roles

| User | What They Do | Platform |
|---|---|---|
| Student | Shares their location, receives alerts, and answers five safety questions. | Mobile Web App |
| Dispatcher | Selects affected zones, monitors student check-ins, and approves responder assignments. | Desktop Dashboard |
| Responder | Accepts assignments and uses 3D navigation to reach students. | Mobile Web App |

## Key Features

- **Interactive 3D Campus Map:** Dispatchers can select specific areas affected by an emergency.
- **Location Tracking:** Identifies students near affected areas using browser-based location services.
- **Targeted Emergency Alerts:** Notifies students in affected zones.
- **Student Safety Check-Ins:** Collects information through five short questions.
- **Automated Risk Identification:** Flags students who report needing help or fail to respond.
- **Responder Coordination:** Helps dispatchers assign responders to students.
- **3D Navigation:** Guides responders through campus to students needing assistance.
- **Student Information:** Provides responders with relevant information about each student's reported situation.

## Tech Stack

*Coming soon.*

## Run Locally

1. From the repository root, install dependencies:

   ```bash
   npm install
   ```

2. Start the Convex backend and follow the setup prompts:

   ```bash
   npm run dev:backend
   ```

   Leave it running.

3. Create `frontend/.env.local` and set `NEXT_PUBLIC_CONVEX_URL` to the `CONVEX_URL` value from `backend/.env.local`.

4. In a second terminal, start the frontend:

   ```bash
   npm run dev:frontend
   ```

5. Open [http://localhost:3000](http://localhost:3000).

## Our Goal

Bear Call transforms traditional campus emergency alerts from one-way broadcasts into an organized emergency response system.

Instead of simply notifying students that an emergency is happening, Bear Call helps campus staff determine who needs help, locate them, and guide responders directly to them.
