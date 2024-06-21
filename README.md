# SqlQuery

select p.name, c.name
from products p
left join productcategories pc on p.id = pc.productid
left join categories c on pc.categoryid = c.id
