# Aggregations-
Aggregations

class College{

    String cname;

    int tstu;

    String  addr;

    College(String cname, int tstu, String  addr){

        this.cname=cname;

        this.tstu=tstu;

        this.addr=addr;

    }

    void met(){

        System.out.println("College name is : "+ cname);

        System.out.println("Total students : "+ tstu);

        System.out.println("College address: "+ addr);

    }

    public static void main(String... details){

        College c=new College("Jawaharlal Nehru Technological University", 50069,"JNTU College of Engineering, Kukatpally, Hyderabad");

        c.met();

    }

}

/*

Aggregation:

- One class has the reference of another class, it is also known as "has-a" relation.

 */

/*

College name is : Jawaharlal Nehru Technological University

Total students : 50069

College address: JNTU College of Engineering, Kukatpally, Hyderabad

 */

