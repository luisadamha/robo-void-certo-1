#include <stdio.h>
#include <stdlib.h>

void LeSensores (void);
void IA (void);
void DriveMotors (void);
int s1, s2, s3;
int m1, m2;

int main(){

while(1){
    void LeSensores();
    void IA();
    void DriveMotors();
}
return 0;
}
void LeSensores(){
    scanf("%d %d %d", &s1, &s2, &s3);
    return;
    }

IA(void){
    if((s1==0) && (s2==0) && (s3==0)) {m1=0; m2=0;}
    if((s1==0) && (s2==1) && (s3==0)) {m1=1; m2=0;}
    if((s1==1) && (s2==0) && (s3==0)) {m1=1; m2=0;}
    if((s1==0) && (s2==0) && (s3==1)) {m1=0; m2=1;}
    if((s1==1) && (s2==0) && (s3==1)) {m1=1; m2=1;}
    if((s1==1) && (s2==1) && (s3==0)) {m1=1; m2=0;}
    if((s1==0) && (s2==1) && (s3==1)) {m1=0; m2=1;}
    if((s1==1) && (s2==1) && (s3==1)) {m1=1; m2=0;}
}

void DriveMotors(){
    printf("m1 = %d, m2 = %d \n", m1, m2);
    return;
}

