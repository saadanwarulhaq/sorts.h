# sorts.h
#ifndef __SORTS_H
#define __SORTS_H

#include <iostream>
#include <vector>
#include <cstdio>
#include <cstring>
#include <cstdlib>
#include <ctime>
#include "list.cpp"
#include "list.h"

using namespace std;

vector<long> InsertionSort(vector<long> nums);
vector<long> MergeSort(vector<long> nums);
vector<long> QuickSortArray(vector<long> nums);

void quickSort( long a[], int first, int last );
long pivot(long a[], int first, int last);
void swap(int& a, int& b);

vector<long> QuickSortList(vector<long> nums);
vector<long> HeapSort(vector<long> nums);
vector<long> BucketSort(vector<long> nums, int max);

#endif
