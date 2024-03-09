
![Screenshot from 2024-03-08 19-34-50](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/0dc5868e-be5d-49d2-922d-d91965716fdf)
<br>Fig. 1 All Instructions are harddcoded and through MEM[NPC] they been sent to IF_ID_IR Register, then PC is incremented  IF_ID_NPC <=NPC+32'd1<br>
<br>
![Screenshot from 2024-03-08 19-43-07](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/fcaf7983-c110-4b57-a3cf-e9b90a16e0f9)
<br> Fig. 2a This is instruction decode stage<br>
<br>
![Screenshot from 2024-03-08 19-52-57](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/a7d6025f-b7e9-4735-b676-546690600233)
<br> Fig. 2b Here we can see General Registers, Instruction Memory and Data memory<br>
<br>
![Screenshot from 2024-03-08 20-06-33](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/bdd6ad7a-e8be-4a19-a6ee-142948e86485)
<br> Fig. 3 After git clone the given RV32 Github repository<br>
<br>
![Screenshot from 2024-03-08 20-08-40](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/586db636-263b-4cf6-8e9a-e0ce1415bdc1)
<br> Fig. 4 To compile verilog files using iverilog simulator<br>
<br>
![Screenshot from 2024-03-08 20-10-55](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/7800d76b-e660-44c4-a1b3-8c03e4e35f64)
<br> Fig. 5 After successful compilation it will generate <b>a.out</b> file<br>
<br>
![Screenshot from 2024-03-08 20-25-31](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/6080b40e-b774-4490-a1d1-bdfc5637a8dc)
<br> Fig. 6 To run the file just in terminal do as shown in figure<br>
<br>
![Screenshot from 2024-03-08 20-31-22](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/96f5cf51-8cef-4212-8951-6d75b785173e)
<br> Fig. 7 It will generate <b>.vcd extension file</b>
<br>
![Screenshot from 2024-03-08 20-36-42](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/c0f8667f-44b2-4e8d-baf0-7ce952cd9749)
<br> Fig. 8 Use <b>gtkwave</b> to open <b>Value Change Dump (vcd) file</b><br>
<br>
![Screenshot from 2024-03-08 21-17-22](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/9e6e3275-5733-4149-93f6-447472e8d914)
<br> Fig. 9a After opening the <b>.vcd file</b> it appears as shown in this figure<br>
<br>
![Screenshot from 2024-03-08 21-23-01](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/d003414b-9d20-4eea-ae93-f69f881c19fc)
<br> Fig. 9b When top-module been selected the view is as shown in the figure<br>
<br>
![Screenshot from 2024-03-08 21-26-07](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/0f477974-551a-4c83-8bcd-05dbb360f85b)
<br> Fig. 9c When instantiated module been selected the view is as shown in the figure<br>
<br>
![Screenshot from 2024-03-08 21-40-27](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/41cee364-fa99-4bf5-a237-61a40bad0fe2)
<br> Fig. 10 All the required signals for the anyalysis purposes can be added the wave shown in figure<br>
<br>
<b> ADD Operation</b>
![Screenshot from 2024-03-08 21-58-22](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/19650184-5edf-4cc7-83fa-b1d4f3227931)
<br> Fig. 11a Figure showing ADDITION operation<br>
![image](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/8cbdb6e6-4ef6-4b35-aba2-53f0f95d92f3)
<br> Fig. 11b Figure showing ADDITION operation with Instruction code<br>
<br>
<b> SUB Operation</b>
![Screenshot from 2024-03-08 22-29-28](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/aa401fae-6d1b-4172-8c2e-17b9b4d8c965)
<br> Fig. 12 Figure showing SUBTRACT operation<br>
<br>
<b> AND Operation </b>
![Screenshot-2](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/7f29bb25-17a9-4e6a-aedc-174e79596f42)

<br> Fig. 13 Figure showing AND operation<br>
<br>
<b> OR Operation </b>
![image](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/ed10b848-8353-40e3-bbd4-e12d66a0789f)
<br> Fig. 14 Figure showing OR operation<br>
<br>

<b> XOR Operation </b>
![image](https://github.com/zakirhussaingit/vlsiriscv/assets/159747370/5d6d98aa-b147-452a-9d5e-625d33ba0305)
<br> Fig. 15 Figure showing XOR operation<br>
<br>









