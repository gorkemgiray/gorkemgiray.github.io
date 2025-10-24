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
      <th scope="col">Organization</th>
      <th scope="col">Degree</th>
      <th scope="col">Title</th>
      <th scope="col">Student</th>
      <th scope="col">Supervisors</th>
      <th scope="col">Link</th>
    </tr>
  </thead>

  <tbody>
    <!-- Example row: replace with your real entries -->
    <tr>
      <td data-label="Year">2027</td>
      <td data-label="Organization">Izmir Institute of Technology</td>
      <td data-label="Degree">Master</td>
      <td data-label="Title">Artificial Intelligence-Enhanced Regression Testing for Large-Scale Software Systems</td>
      <td data-label="Student">Yusuf Emre Beskan</td>
      <td data-label="Supervisors">Prof. Dr. Onur Demirörs; Dr. Görkem Giray</td>
      <td data-label="Link">Ongoing</td>
    </tr>

    <tr>
      <td data-label="Year">2025</td>
      <td data-label="Organization">Eindhoven University of Technology</td>
      <td data-label="Degree">Master</td>
      <td data-label="Title">Towards a Gold-Standard Refactoring Dataset</td>
      <td data-label="Student">Maria Emanuela Calota</td>
      <td data-label="Supervisors">Asst. Prof. Lina Ochoa Venegas; Dr. Görkem Giray; Asst. Prof. Önder Babur</td>
      <td data-label="Link">Under Publication</td>
      <!-- <td data-label="Link">
        <a href="https://example.com/thesis-john-smith.pdf" target="_blank" rel="noopener noreferrer">PDF</a> -->
      </td>
    </tr>

    <tr>
      <td data-label="Year">2023</td>
      <td data-label="Organization">Izmir Institute of Technology</td>
      <td data-label="Degree">Master</td>
      <td data-label="Title">A mutation-based approach to alleviate the class imbalance problem in software defect prediction</td>
      <td data-label="Student">Dinçer Güner</td>
      <td data-label="Supervisors">Prof. Dr. Onur Demirörs; Dr. Görkem Giray</td>
      <td data-label="Link"><a href="https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=a0OMTmEd_3mfOBxT8SiBTOuxw1WkE_y0xTUHhxIr-PRxdN6xi2HDNw2R21n3Id4b" target="_blank" rel="noopener noreferrer">PDF</a></td>
    </tr>
  </tbody>
</table>

<!-- Referee / Program Committee Membership table -->
<style>
  .committee-table {
    width: 100%;
    border-collapse: collapse;
    font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    margin: 0.75rem 0;
  }

  .committee-table thead th {
    text-align: left;
    padding: 0.6rem 0.75rem;
    border-bottom: 2px solid #e6e6e6;
    font-weight: 600;
  }

  .committee-table tbody td {
    padding: 0.5rem 0.75rem;
    border-bottom: 1px solid #f0f0f0;
    vertical-align: top;
  }

  .committee-table tbody tr:last-child td {
    border-bottom: none;
  }

  /* Responsive (mobile view) */
  @media (max-width: 720px) {
    .committee-table thead { display: none; }
    .committee-table, 
    .committee-table tbody, 
    .committee-table tr, 
    .committee-table td {
      display: block;
      width: 100%;
    }
    .committee-table tr {
      margin-bottom: 0.75rem;
      border: 1px solid #eee;
      border-radius: 6px;
      padding: 0.5rem;
    }
    .committee-table td {
      border: none;
      padding: 0.4rem 0.5rem;
    }
    .committee-table td::before {
      content: attr(data-label);
      display: inline-block;
      font-weight: 600;
      width: 7.5rem;
      min-width: 7.5rem;
    }
  }
</style>

<table class="committee-table" aria-describedby="committee-caption">
  <caption id="committee-caption" style="text-align:left; font-weight:600; padding-bottom:0.4rem;">
    Referee / Program Committee Membership
  </caption>

  <thead>
    <tr>
      <th scope="col">Year(s)</th>
      <th scope="col">Role</th>
      <th scope="col">Venue</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td data-label="Year">2016 - 2026</td>
      <td data-label="Role">PC Member</td>
      <td data-label="Venue">National Software Engineering Conference (Ulusal Yazılım Mühendisliği Sempozyumu)</td>
    </tr>
    <tr>
      <td data-label="Year">2025</td>
      <td data-label="Role">PC Member</td>
      <td data-label="Venue">ACM/IEEE International Symposium on Empirical Software Engineering and Measurement</td>
    </tr>
    <tr>
      <td data-label="Year">2023 - 2025</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Empirical Software Engineering</td>
    </tr>
    <tr>
      <td data-label="Year">2019, 2022, 2024 - 2025</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Journal of Systems and Software</td>
    </tr>
    <tr>
      <td data-label="Year">2024 - 2025</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Software Quality Journal</td>
    </tr>
    <tr>
      <td data-label="Year">2021, 2024 - 2025</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Journal of Software: Evolution and Process</td>
    </tr>
    <tr>
      <td data-label="Year">2025</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Software Testing, Verification and Reliability</td>
    </tr>
    <tr>
      <td data-label="Year">2023, 2025</td>
      <td data-label="Role">PC Member</td>
      <td data-label="Venue">Evaluation and Assessment in Software Engineering – Industry Track</td>
    </tr>
    <tr>
      <td data-label="Year">2022 - 2025</td>
      <td data-label="Role">PC Member</td>
      <td data-label="Venue">International Workshop on Software Measurement and Conference on Software Measurement Product Measurement</td>
    </tr>
    <tr>
      <td data-label="Year">2022 - 2025</td>
      <td data-label="Role">PC Member</td>
      <td data-label="Venue">Euromicro Conference on Software Engineering and Advanced Applications</td>
    </tr>
    <tr>
      <td data-label="Year">2023</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Transactions on Software Engineering</td>
    </tr>
    <tr>
      <td data-label="Year">2023</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Information Software and Technology</td>
    </tr>
    <tr>
      <td data-label="Year">2023</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Innovations in Systems and Software Engineering</td>
    </tr>
    <tr>
      <td data-label="Year">2022</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">IEEE Transactions on Neural Networks and Learning Systems</td>
    </tr>
    <tr>
      <td data-label="Year">2022</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Information Technology and Management</td>
    </tr>
    <tr>
      <td data-label="Year">2021</td>
      <td data-label="Role">Organization Co-Chair</td>
      <td data-label="Venue">National Software Engineering Conference (Ulusal Yazılım Mühendisliği Sempozyumu)</td>
    </tr>
    <tr>
      <td data-label="Year">2021</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">IEEE Software</td>
    </tr>
    <tr>
      <td data-label="Year">2021</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Expert Systems</td>
    </tr>
    <tr>
      <td data-label="Year">2020 - 2021</td>
      <td data-label="Role">PC Member</td>
      <td data-label="Venue">International Conference on the Software and Systems Process</td>
    </tr>
    <tr>
      <td data-label="Year">2019 - 2021</td>
      <td data-label="Role">Editorial Review Board Member</td>
      <td data-label="Venue">International Journal of Cognitive Informatics and Natural Intelligence (IJCINI), IGI Global</td>
    </tr>
    <tr>
      <td data-label="Year">2019 - 2020</td>
      <td data-label="Role">PC Member</td>
      <td data-label="Venue">International Conference on Software Technologies (ICSOFT)</td>
    </tr>
    <tr>
      <td data-label="Year">2019</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Journal of Computer Science and Technology</td>
    </tr>
    <tr>
      <td data-label="Year">2012, 2015, 2016, 2019</td>
      <td data-label="Role">Referee</td>
      <td data-label="Venue">Turkish Journal of Electrical Engineering and Computer Sciences</td>
    </tr>
    <tr>
      <td data-label="Year">2018</td>
      <td data-label="Role">PC Member</td>
      <td data-label="Venue">International Workshop on Software Engineering Education for Millennials</td>
    </tr>
    <tr>
      <td data-label="Year">2016 - 2018</td>
      <td data-label="Role">PC Member</td>
      <td data-label="Venue">National Software Architecture Conference (Ulusal Yazılım Mimarisi Konferansı)</td>
    </tr>

  </tbody>
</table>
