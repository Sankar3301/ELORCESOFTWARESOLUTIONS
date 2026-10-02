# Gaincon live-site review and redesign decisions

Reviewed 3 October 2026 at https://gaincon.com/ after following the supplied share.google link. The live site loaded as Gaincon Consulting Services. This records what was visible during review; the redesign uses the supplied Elorce name, phone and address in place of the live contact identity.

## Observed structure and information architecture

- Shared header with Gaincon logo and a responsive side-slide navigation. Main links: Home, About us, Services, Staffing, Careers; a Contact us action also appears in the menu.
- Home: hero carousel/message and Discover CTA; firm introduction; three “why choose us” points; five-client carousel; recruiting CTA; shared footer.
- About: company introduction, service/company history, stated 98.4% client retention/repetition rate, mission and vision, contact CTA.
- Services: business process re-engineering introduction; IT services grouped into SAP/ERP, Microsoft technologies, web technologies, database administration, and mobile/gaming applications; contact CTA.
- Staffing: staffing introduction and three engagement types (direct hire, contract on client payroll, contract on Gaincon payroll); three-image carousel; four-step process (search brief, screen/vet, interview, negotiate/close); contact CTA.
- Careers: introductory copy; searchable current-job list and Filter by checkbox; one Mobile Developer listing in Johannesburg; contact CTA.
- Mobile Developer job detail: job brief, responsibilities, requirements, job type and location, then application form.
- Contact: South Africa and India office/contact details, followed by four-field enquiry form.
- Shared footer: social icons, South Africa and India office contacts, copyright, back-to-top control.

## Content, contact details and visual assets

- The live site describes IT recruitment/staffing, IT services and business process re-engineering. It names Alcove, Weblinx, Elixirasia, Promantra and Scubus as clients.
- Live-site South African phone/address differ from the user-supplied replacements. The redesign uses 011 277 2417 and G 76 Midway Gardens, 315 First Road, Halfway House, Midrand, Johannesburg 1685. India contact information and old company emails were omitted because they do not belong to the supplied new identity.
- The live home hero, logo, client carousel and staffing imagery were present. Their underlying asset files were not incorporated into this static redesign. Client names are presented as text, not as copied logos. The new brand mark is a small original typographic mark; the home page uses an editorial team photograph from Unsplash.
- The reported 98.4% retention figure is kept only with clear attribution to the original site. The old “over two years” claim was not carried forward because its age makes it unreliable.

## Calls to action and forms

- Original CTAs route visitors from Home/About/Services/Staffing/Careers to Contact. The menu also links across the five main sections.
- Original Contact form exposed name, email, subject, message and “Send a message”.
- Original Careers page supports role search and filtering; the live listing links to a dedicated job page.
- Original application flow asks for name, email, phone, cover letter, CV/Resume (.pdf, .doc, .docx), and agreement to data handling before Submit.
- The redesign keeps direct role search/filtering, a detailed Mobile Developer role, all key application fields, and an enquiry form. The supplied material does not include an email address, form endpoint, or recruitment system credentials. Accordingly, the static preview validates forms locally and explicitly tells visitors that no data is sent or stored. A real launch needs the company’s chosen form/recruitment endpoint and privacy wording.
- Phone links use the supplied South African number. Directions open a Google Maps search only when selected.

## UX, interaction and responsive behavior

- The desktop live site’s side-slide menu, hero/client/staffing carousels, job search/filter, enquiry form, job application form and back-to-top link were confirmed in the visible accessibility tree.
- Review was performed at desktop viewport. The source site indicates a separate responsive/mobile menu in its accessibility tree; exact narrow-screen visual behavior was not independently verified during this review. The redesign deliberately implements a touch-friendly collapsed mobile navigation, single-column hero/forms/cards, compact typography, and responsive grids.
- The redesign replaces the older slide-and-section flow with clearer service pathways, repeated but focused Contact CTAs, scannable service/engagement cards and a dedicated hiring process.
- Keyboard focus styles, skip-to-content, labelled fields, semantic headings, phone links, form validation, reduced-motion support and descriptive image text are included. Motion is limited to subtle reveal/hover transitions.

## Launch follow-up

Before publishing, confirm the vacancy is still open, approve any retained numerical or client claims, provide a real contact-form and application destination, confirm data-retention/privacy wording, and supply any official Elorce logo, email address or social links. The implementation is a static website preview and does not publish to or modify the live Gaincon site.
