---
layout: archive
title: "Activities"
permalink: /activities/
author_profile: true
---

<!-- Masters Theses Supervised table -->
<style>
  .theses-table {
    width: 100%;
    border-collapse: collapse;
    font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    margin: 0.75rem 0;
  }

  .theses-table thead th {
    text-align: left;
    padding: 0.6rem 0.75rem;
    border-bottom: 2px solid #e6e6e6;
    font-weight: 600;
  }

  .theses-table tbody td {
    padding: 0.5rem 0.75rem;
    border-bottom: 1px solid #f0f0f0;
    vertical-align: top;
  }

  .theses-table tbody tr:last-child td {
    border-bottom: none;
  }

  .theses-table a {
    text-decoration: none;
  }

  /* Small-screen responsive: stack cells and show labels */
  @media (max-width: 720px) {
    .theses-table thead { display: none; }
    .theses-table, 
    .theses-table tbody, 
    .theses-table tr, 
    .theses-table td {
      display: block;
      width: 100%;
    }
    .theses-table tr {
      margin-bottom: 0.75rem;
      border: 1px solid #eee;
      border-radius: 6px;
      padding: 0.5rem;
    }
    .theses-table td {
      border: none;
      padding: 0.4rem 0.5rem;
    }
    .theses-table td::before {
      content: attr(data-label);
      display: inline-block;
      font-weight: 600;
      width: 7.5rem;
      min-width: 7.5rem;
    }
  }
</style>

<table class="theses-table" aria-describedby="theses-caption">
  <caption id="theses-caption" style="text-align:left; font-weight:600; padding-bottom:0.4rem;">
    Masters Theses Supervised
  </caption>

  <thead>
    <tr>
      <th scope="col">Year</th>
      <th scope="col">Student</th>
      <th scope="col">Supervisors</th>
      <th scope="col">Link</th>
    </tr>
  </thead>

  <tbody>
    <!-- Example row: replace with your real entries -->
    <tr>
      <td data-label="Year">2024</td>
      <td data-label="Student">Jane Doe</td>
      <td data-label="Supervisors">Prof. A. Advisor; Prof. B. Mentor</td>
      <td data-label="Link">
        <a href="https://example.com/thesis-jane-doe.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
      </td>
    </tr>

    <tr>
      <td data-label="Year">2023</td>
      <td data-label="Student">John Smith</td>
      <td data-label="Supervisors">Prof. A. Advisor</td>
      <td data-label="Link">
        <a href="https://example.com/thesis-john-smith.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
      </td>
    </tr>

    <!-- Add more rows below -->
    <!--
    <tr>
      <td data-label="Year">YYYY</td>
      <td data-label="Student">Student Name</td>
      <td data-label="Supervisors">Supervisor 1; Supervisor 2</td>
      <td data-label="Link"><a href="URL-to-thesis" target="_blank" rel="noopener noreferrer">PDF / Link</a></td>
    </tr>
    -->
  </tbody>
</table>

