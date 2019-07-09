npm i   --- complete


create db named "unit2_assessment" --- complete
    createdb unit2_assessment

create model --- complete
sequelize model:create --name widget --attributes description:string,quantity:integer

migrate model --- complete
sequelize db:migrate

check for table --- complete

created index.ejs

root route --- complete
linked css stylesheet --- complete

no widgets exist displayed when db is empty.

<%=widget.description%>
<%=widget.quantity%>


    <% widgets.forEach(widget){ %>
        <div class="section">
        <h2>Descript</h2>
        <p>Quantity: </p>
        </div>
    <% }; %>
<% }; %>


<%if (widgets.length === 0) { %>
    <h3> No widgets exist</h3>
<% } else { %>
<% widgets.forEach(widget){ %>
    <p> <%=%> </p>

<% } %>
<% };%>