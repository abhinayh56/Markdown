# Control System

1. Classical control
2. Modern control

asasas
1. P
2. D
3. PD
4. PI
5. PID
    1. Standard form
    2. Parallel form

**Miscellaneous**
1. P
2. I
3. D
4. D_LPF_1
5. PI
6. PD
7. PD_LPF_1
8. PID
9. PID_LPF_1
10. PID_LPF_1_FF
11. PID_P
12. PID_S
13. PID_GS

```
class Controller_name{
    public:
        Controller_name();
        void init();
        void set_param();
        double update();
        void reset();
        void merge();

        void set_param_1();
        void set_param_2();
        void get_param_1();
        void get_param_2();

    private:
        double param_1;
        double param_2;
};
```