# generics
class Myclass <T extends comparable<T>>
{
    T[] vals;
    My class [T[]0]
    {
        vals=0;
    }
    public T min()
    {
        Tv=vals[0];
        for(int i=0;i<valslength;i++)
        if(vals[i].compareTo(v)<0)
        v=vals[i];
        return v;
    }
    public T max()
    {
        Tv=vals[0];
        for(int i=0;i<valslength;i++)
        if(vals[i].compareTo(v)>0)
        v=vals[i];
        return v;  
    }
}
class Main
{
    public static void main(String[] args)
    {
    int i;
    integer inum[]={10,20,30,40,50};
    character chs[]={'s','r','e','y','a'};
    double d[]={20.2,30.2,40.2,50.2,60.2};
    My class <intiger>job=new Myclass<intiger>(inum);
    My class <character>cob=new Myclass<character>(chs);
    My class <double>dob=new Myclass<double>d();
    System.out.println("max value in inum"+job.max());
    System.out.println("min value in inum"+job.min());
    System.out.println("max value in chs"+cob.max());
    System.out.println("min value in chs"+cob.min());
    System.out.println("max value in d"+dob.max());
    System.out.println("min value in d"+dob.min());
    }
}
