# Internet-Programming-Spring-2026-

**Tailwind functions and styles used**

**html.index**
lg:grid-cols-4: Used in the main container to create the asymmetrical 4-column layout for the sidebar and content.
lg:col-span-3: Used on the <main> tag to ensure the content area takes up three-quarters of the screen on large displays.
flex flex-col: Used in the sidebar and header to stack elements vertically.
container mx-auto: Used in the header and main wrapper to center the content and prevent it from hitting the screen edges.
sticky: Applied to the navigation menu so it stays visible as you scroll through the impact analysis.
top-8: Sets the specific vertical offset for the sticky navigation.
gap-8: Defines the uniform whitespace between your sidebar and main content blocks.
overflow-x-auto: Applied to the table wrapper to ensure the Impact Matrix is scrollable and doesn't break on mobile devices.

**style.css**

bg-slate-50: Used for the global page background to provide a soft, professional neutral tone.
bg-slate-900: Applied to the header and table headers for high-authority, dark-mode contrast.
text-cyan-500: Used as the primary accent color for the breadcrumbs and section borders to represent a technical aesthetic.
rounded-xl: Defines the modern, 12px corner radius used on your content cards.
shadow-sm: Provides the subtle "lift" effect for your white content blocks against the gray background.
border-l-4: Used on section titles (e.g., "01. Abstract") to create a vertical visual anchor.
leading-relaxed: Applied to paragraph text to optimize readability for your informative content.
font-mono: Used for the breadcrumbs and footer to signal a "Computer Science" or technical context.
uppercase: Applied to the table headers and navigation labels to create a clear visual hierarchy.
tracking-widest: Used on the small-caps labels to improve legibility and provide a modern look.
transition-all: Enables the smooth color shifts on your navigation links during a hover state.
px-4 / py-10: Standardized padding tokens used to maintain consistent vertical and horizontal rhythm across all sections.**
