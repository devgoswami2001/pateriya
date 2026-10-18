# Reception demo

Open `/login` in the local app. Email: `reception@clinic.demo`. Password: `ClinicDemo123`.

Reception can create scheduled appointments, register walk-ins, search returning patients, filter the schedule, check patients in, reschedule, cancel and mark no-shows. Walk-ins receive a queue token immediately. Scheduled visits receive one at check-in. Clinic slots run from noon to 3 PM, using India dates.

Public demo bookings appear in the same schedule. To try the doctor handoff, sign out and sign in as `doctor@clinic.demo` with the same password, then open Patient queue. Completing the consultation updates the shared visit status.

The doctor demo includes the checked-in queue, visit vitals, consultation notes, medicines, investigations, previous visits, prescription history and report review. Complete a reception check-in first to create a fresh doctor-queue visit.

Records persist in localStorage in this browser. Demo sessions use sessionStorage. This is client-side simulation, not secure authentication, a multi-user backend, or production patient-record storage. Use synthetic data only. No SMS, payment or email is sent. Nothing has been published by this change.

Checks: `npm run build` and `node --test src/features/reception/service.test.js`.
