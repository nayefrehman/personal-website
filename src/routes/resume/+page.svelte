<script lang="ts">
  import Seo from "$lib/components/Seo.svelte";
  import Workplace from "./Workplace.svelte";
</script>

<Seo
  title="Naif Rehman – Resume"
  description="Computer Engineering student focused on data science, software development, and applied engineering projects."
/>

<!-- ================= EDUCATION ================= -->
<section class="layout-md py-12">
  <h2 class="heading2">Education</h2>

  <div class="mb-4">
    <div class="flex justify-between items-end">
      <h3 class="text-black text-lg">Queen’s University</h3>
      <div class="text-neutral-500 mb-0.5">Expected May 2028</div>
    </div>

    <p class="byline">Bachelor of Applied Science, Computer Engineering</p>
    <p class="byline">Kingston, ON</p>
  </div>

  <h4 class="font-medium mt-4 mb-1">Related Coursework:</h4>
  <ul>
    <li>ECE 278 Data Structures & Algorithms</li>
    <li>ECE 279 Object Oriented Programming</li>
    <li>ECE 274 Computer Architecture</li>
    <li>ECE 274 Data Science & Analytics</li>
  </ul>
</section>

<!-- ================= EXPERIENCE ================= -->
<section class="layout-md py-12">
  <h2 class="heading2">Experience</h2>

  <Workplace
    title="Engineering Lab – Data Science & Analytics"
    company="Queen’s University"
    dates="Sep 2024 – Dec 2024"
    location="Kingston, ON"
  >
    <li>
      Collected, structured, and maintained experimental datasets using Excel for accurate analysis and reporting.
    </li>
    <li>
      Performed statistical analysis and linear regression using Excel and Python (Jupyter Notebook), validating relationships between variables.
    </li>
    <li>
      Conducted data cleaning and quality checks by identifying inconsistencies and outliers to improve dataset reliability.
    </li>
    <li>
      Produced technical reports with tables and charts summarizing experimental findings.
    </li>
  </Workplace>

  <Workplace
    title="Automated Water Filtration System – Engineering Design Project"
    company="Queen’s University"
    dates="Sep 2024 – Dec 2024"
    location="Kingston, ON"
  >
    <li>
      Collaborated in a team to design and build a water filtration prototype.
    </li>
    <li>
      Modeled mechanical components in SolidWorks for system assembly.
    </li>
    <li>
      Assisted in Arduino programming for timed rotation and controlled dispensing.
    </li>
    <li>
      Tested and calibrated system for consistent performance and reliability.
    </li>
  </Workplace>

</section>

<!-- ================= PROJECTS ================= -->
<section class="layout-md py-12">
  <h2 class="heading2">Projects</h2>

  <Workplace
    title="Walking vs Running Classifier"
    company="Personal Project"
    dates="Jan 2025 – Present"
    location="Mississauga, ON"
  >
    <li>
      Built a data pipeline in Python (Pandas, NumPy) to process accelerometer data for human activity recognition.
    </li>
    <li>
      Cleaned and segmented time-series data using noise reduction and missing value handling techniques.
    </li>
    <li>
      Extracted statistical features (mean, variance, range) to analyze activity patterns.
    </li>
  </Workplace>

  <Workplace
    title="Bike Share Availability Analytics Dashboard"
    company="Personal Project"
    dates="Feb 2025 – Present"
    location="Mississauga, ON"
  >
    <li>
      Built a real-time dashboard using Python (Streamlit, Pandas) with City of Toronto Bike Share API data.
    </li>
    <li>
      Processed and cleaned API data to ensure accurate station-level tracking.
    </li>
    <li>
      Created interactive geospatial visualizations to monitor bike and dock availability.
    </li>
  </Workplace>
</section>

<style lang="postcss">
  b {
    @apply font-medium;
  }

  ul {
    @apply list-disc pl-7 marker:text-neutral-400;
  }

  .byline {
    @apply font-serif italic;
  }
</style>