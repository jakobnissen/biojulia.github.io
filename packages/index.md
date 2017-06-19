---
title: BioJulia Packages
subtitle: Software Packages developed and maintained by the BioJulia organisation.
layout: standardpage
---

<table class=".table-hover" style="font-size:20px;width:100%">
    <col align="left">
    <col align="center">
    <col align="right">
    <tr class="spaceunder">
        <th>Package</th>
        <th>Description</th>
        <th>Links</th>
    </tr>
    {% for package in site.data.packages %}
    <tr class="spaceunder">
        <td>{{ package.name }}</td>
        <td>{{ package.tagline }}</td>
        <td>
            <center>
            <a href="{{ package.link }}"><span class="fa fa-github fa-lg"></span></a>
            <a href=""><span class="fa fa-book fa=lg"></span></a>
            </center>
        </td>
    </tr>
    {% endfor %}
</table>
