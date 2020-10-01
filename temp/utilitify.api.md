## API Report File for "utilitify"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

// @public (undocumented)
export type AllType = undefined | null | boolean | Buffer | number | string | Date | RegExp | Error | Iterator<any> | any[] | Function | Promise<any> | Map<any, any> | WeakMap<any, any> | Set<any> | WeakSet<any> | TypedArray | IKeyValue<any> | any;

// @public (undocumented)
export const cloneArrayBuffer: (val: ArrayBuffer) => ArrayBuffer;

// @public (undocumented)
export const cloneArrayDeep: (arr: AllType[], instanceClone?: Function | undefined) => AllType[];

// @public (undocumented)
export const cloneDeep: (val: AllType, instanceClone?: Function | undefined) => AllType;

// @public (undocumented)
export const cloneObjectDeep: (obj: AllType, instanceClone?: Function | undefined) => AllType;

// @public (undocumented)
export const cloneRegExp: (val: RegExp) => RegExp;

// @public (undocumented)
export const cloneShallow: (val: AllType) => AllType;

// @public (undocumented)
export const cloneSymbol: (val: symbol) => symbol;

// @public (undocumented)
export const cloneTypedArray: (val: TypedArray) => TypedArray;

// @public (undocumented)
export const compose: (...funcs: Function[]) => AllType;

// @public (undocumented)
export const delIn: (obj: AllType, path: string | string[]) => AllType;

// @public
export function difference<T>(object: T, base?: T | any[] | object): T | T[] | Record<string, any>;

// @public (undocumented)
export function getArrayOfObjectsWithoutProp(arr: AllType[], propName: string): AllType[];

// @public (undocumented)
export function getJsonFromString(str: string): IJson;

// @public (undocumented)
export function getObjectFromArrayByProp(arr: AllType[], prop: string): AllType;

// @public (undocumented)
export function getObjectWithoutEmptyPropsFrom(object: object): object;

// @public (undocumented)
export function getObjectWithoutUndefinedPropsFrom(object: object): object;

// @public (undocumented)
export function getTruncatedString(str: string, length: number, punctuationMark?: Maybe<string>): string;

// @public (undocumented)
export interface IArrayBufferConstructor {
    // (undocumented)
    new (byteLength: number): ArrayBuffer;
}

// @public (undocumented)
export interface IJson {
    // (undocumented)
    [key: string]: AllType;
}

// @public (undocumented)
export interface IKeyValue<T> {
    // (undocumented)
    [key: string]: T;
}

// @public (undocumented)
export interface IRegExpConstructor {
    // (undocumented)
    new (source: string, flags: string): RegExp;
}

// @public (undocumented)
export function isDifference(object: any, base?: any): boolean;

// @public (undocumented)
export function isJsonString(str: string): boolean;

// @public (undocumented)
export function isNil(value: AllType): boolean;

// @public (undocumented)
export function isNull(value: AllType): boolean;

// @public (undocumented)
export const isObject: (val: AllType) => boolean;

// @public (undocumented)
export const isObjectObject: (o: AllType) => boolean;

// @public (undocumented)
export const isPlainObject: (o: AllType) => boolean;

// @public (undocumented)
export function isUndefined(value: AllType): boolean;

// @public (undocumented)
export interface ITypedArrayConstructor {
    // (undocumented)
    new (buffer: ArrayBuffer, byteOffset: number, length: number): TypedArray;
}

// @public (undocumented)
export type Maybe<T> = T | null | undefined;

// @public (undocumented)
export const mergeDeep: (orig: AllType, ...rest: AllType[]) => AllType;

// Warning: (ae-forgotten-export) The symbol "PropertyPath" needs to be exported by the entry point index.d.ts
//
// @public (undocumented)
export function setIn<TReturn, TValue>(obj: TReturn, value: TValue, field: PropertyPath): TReturn;

// @public (undocumented)
export const setInWithPath: (obj: any, value: any, path: string | string[], pathIndex: number) => any;

// @public (undocumented)
export function toPascalCase(string: string): string;

// @public (undocumented)
export type TypedArray = Int8Array | Uint8Array | Uint8ClampedArray | Int16Array | Uint16Array | Int32Array | Uint32Array | Float32Array | Float64Array;

// Warning: (ae-forgotten-export) The symbol "United" needs to be exported by the entry point index.d.ts
//
// @public (undocumented)
export const union: (init: United[], ...rest: United[]) => United[];

// @public (undocumented)
export function upsertObjectToArray(arr: AllType[], prop: object, newVal: AllType): void;


// (No @packageDocumentation comment for this package)

```