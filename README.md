# hello-world
My first repository
record Pool(String address, int volumeOfWater, int maxNumOfVisitors) {
    static int count = 12;
//private int x = 15;

    Pool() {
        this("no address", 10, 2);
    }

    @Override
    public String address() {
        return address;
    }

    @Override
    public int volumeOfWater() {
        return volumeOfWater;
    }

    @Override
    public int maxNumOfVisitors() {
        return maxNumOfVisitors;
    }

    public static int getcount() {
        return count;
    }


    @Override
    public String toString() {
        return "Pool{" +
                "address='" + address + '\'' +
                ", volumeOfWater=" + volumeOfWater +
                ", maxNumOfVisitors=" + maxNumOfVisitors +
                '}';
    }
}

