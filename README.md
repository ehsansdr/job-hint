# job-hint
we have to have CRUD operation amd many other opertaion thta is some kind of the like how we want to READ data by monitoring or by excel or any thing else
# job-hint
we have to have CRUD operation amd many other opertaion thta is some kind of the like how we want to READ data by monitoring or by excel or any thing else
 first we have PO class that has many layers that help us to make crud and so we need to extend that 
in company we have po


and the
we have xxxVO.java extends PO 
annotated with : @MappedSuperclass
we put our deffrent culoumn in here but in the end PO add another culomn to it
and we have xxx.java extends xxxVO.java wwe have namedQuery that have same value and check short number (shenase)
like :

    private String firstName;
    private String lastName;
    private String contractApplicantShortName;
    private BigDecimal profit; // use BigDecimal ,it is more power full than the float
    private Date startDate;
    private Contract contract;

do not set id as primery ke it will do add that be care ful about the short name 
HAVE GETTER AND SETTER 
and set the @Culomn above the Getter method as snake case 


and that we have xxxView.java 
