# pseudocodigo
##Crear un repositorio el cual deberá definir mediante pseudocódigo las clases,atributos y métodos para un sistema de una botillería.Centrarse en la parte de Inventario y NO en la Transaccional
 
Class Product
    {
       ##Atributo##
        
        Name = '' #nombre del producto
        Price_buy = 0 #precio de compra
        price_sell = 0 #precio de venta
        Stock = 0 #cantidad de producto
        Elaboration_date = '' #fecha de elaboración 
        Expiration_date = '' #fecha de expiración
        Bar_code = '' #codigo de barra
        Quantity = '' #cantidad del producto
        Critical_Stock = '' #cantidad crítica del producto
        Work_Hours = 0 #horas de trabajo
        Overtime_Work = 0 #horas extra de trabajo

        ##Fin  de los atributos##

    }

    Class Workers
    {
       ##Atributos##
        
        Name = '' #nombre del empleado
        Sex = '' #sexo del empleado
        Nationality = '' #nacionalidad del empleado
        Date_Contract = '' #tipo de contrato del empleado
        Salary = 0 #el salario correspondiente del empleado
        Work_Area = '' #el área en la cual trabaja el empleado


        ##Fin atributos##

        ##Metodos##

        Offer = 0 #precio de oferta
        
        Critical_Stock_Warning  = '' #aviso de que se está agotando el stock
        
        Expiration_Date_Warning = 0 #aviso de que esta por llegar la fecha de expiración
        
        Dismissal_Notice = '' #aviso de despido
        
        Change_Of_Work_Area = '' #aviso de cambio de area de trabajo
        
        ##Fin métodos##

    }
