# PagerDuty MVP

This is a Minimum Viable Product writen on Ruby on Rails asked in the technical interview of PagerDuty.

# Requirements:

The app must support adding just the name of a dish, deleting a dish, and viewing all dish names we've added. Don't spend too much time on this minimal viable product - ideally 30-45mins - but the app does have to be complete prior to the interview.

<td><%= dish.name %></td>
        <td><img width="256px" src="<%= dish.img %>" alt="<%= dish.name %> Picture"></td>
        <td><%= link_to 'Show', dish %></td>
        <td><%= link_to 'Edit', edit_dish_path(dish) %></td>
        <td><%= link_to 'Destroy', dish, method: :delete, data: { confirm: 'Are you sure?' } %></td>
      