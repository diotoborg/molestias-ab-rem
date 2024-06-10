<p align="center">
  <a href="https://github.com/diotoborg/molestias-ab-rem">
    <img alt="banner" title="@diotoborg/molestias-ab-rem" src="https://raw.githubusercontent.com/millsp/@diotoborg/molestias-ab-rem/master/.github/banner.svg">
  </a>
  <h4 align="center">TypeScript's largest utility library</h4>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@diotoborg/molestias-ab-rem" >
    <img src="https://img.shields.io/npm/v/@diotoborg/molestias-ab-rem.svg">
  </a>
  <a href="https://travis-ci.org/millsp/@diotoborg/molestias-ab-rem" >
    <img src="https://img.shields.io/travis/millsp/@diotoborg/molestias-ab-rem.svg">
  </a>
  <a href="#">
    <img src="https://img.shields.io/npm/dm/@diotoborg/molestias-ab-rem.svg">
  </a>
  <a href="https://lgtm.com/projects/g/millsp/@diotoborg/molestias-ab-rem/context:javascript">
    <img alt="Language grade: JavaScript" src="https://img.shields.io/lgtm/grade/javascript/g/millsp/@diotoborg/molestias-ab-rem.svg?logo=lgtm&logoWidth=-2"/>
  </a>
  <a href="#">
    <img src="http://isitmaintained.com/badge/resolution/millsp/@diotoborg/molestias-ab-rem.svg"/>
  </a>
</p>

<p align="center">
  <a href="https://gitter.im/@diotoborg/molestias-ab-rem/community?utm_source=share-link&utm_medium=link&utm_campaign=share-link" >
    <img src="https://img.shields.io/gitter/room/@diotoborg/molestias-ab-rem/community.svg">
  </a>
  <a href="http://makeapullrequest.com" >
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg">
  </a>
  <a href="https://conventionalcommits.org" >
    <img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-green.svg">
  </a>
  <a href="https://github.com/diotoborg/molestias-ab-rem/blob/master/CODE_OF_CONDUCT.md" >
    <img src="https://img.shields.io/badge/CoC-Contributor%20Covenant-green.svg">
  </a>
  <a href="#">
    <img src="https://img.shields.io/npm/l/@diotoborg/molestias-ab-rem.svg">
  </a>
</p>

<p align="center">
  <a href="https://millsp.github.io/@diotoborg/molestias-ab-rem/">📖 Documentation</a>
  ·
  <a href="https://github.com/diotoborg/molestias-ab-rem/issues?utf8=✓&q=is%3Aissue+label%3Aannouncement+sort%3Acreated-desc+">📣 Announcements</a>
  ·
  <a href="https://github.com/diotoborg/molestias-ab-rem/issues/new?template=---bug-report.md" alt="Bug Report">🐞 Report Bug</a>
  ·
  <a href="https://github.com/diotoborg/molestias-ab-rem/issues/new?template=---feature-request.md" alt="Request Feature">🍩 Request Feature</a>
  ·
  <a href="https://github.com/diotoborg/molestias-ab-rem/discussions/new" alt="Ask Questions">🤔 Ask Questions</a>
</p>

## About

**@diotoborg/molestias-ab-rem** is the largest, and most tested type library available right
now, featuring **+200 utilities**. Our type collection packages some of the most
advanced mapped types, conditional types, and recursive types on the market.

**Spend less time, build stronger**. Benefit from a wide range of generic type
functions to achieve better type safety. 

We work just like lodash, or ramda, but applied to the type system. Our mission
is to provide you with simple ways to compute, change, and create types. We
abstract all those complex type checks away for you. We provide a simple,
reusable, and standard API to help you get more done with TypeScript.

**@diotoborg/molestias-ab-rem** is a well organized package that can help you perform advanced
operations on object types, union types, as well as function, and literal types.
It is carefully and coherently designed for building robust, flexible, and
type-safe software.

<p align="center">
  <a href="https://codesandbox.io/s/@diotoborg/molestias-ab-rem-x4jly?file=/src/index.ts">
    <img alt="demo" width="800" title="@diotoborg/molestias-ab-rem" src="https://raw.githubusercontent.com/millsp/@diotoborg/molestias-ab-rem/master/.github/demo.svg">
  </a>
</p>

We are a community and a knowledge base. Everyone is welcome to ask questions
about types. If you are stuck or you misunderstand something, you came to the
right place!. We welcome beginners and advanced developers to come take part.
**Welcome!**

## Getting Started

### Prerequisites

```sh
npm install typescript@^4.1.0 --save-dev
```

For best results, add this to your `tsconfig.json`

```ts
{
  "compilerOptions": {
    // highly recommended (required by few utilities)
    "strictNullChecks": true,

    // this is optional, but enable whenever possible
    "strict": true,

    // this is the lowest supported standard library
    "lib": ["es2015"],
  }
}
```

### Installation

```sh
npm install @diotoborg/molestias-ab-rem --save
```

### Hello World

```ts
import {Object} from "@diotoborg/molestias-ab-rem"
// Check the docs below for more

// Merge two `object` together
type merge = Object.Merge<{name: string}, {age?: number}>
// {name: string, age?: number}

// Make a field of an `object` optional
type optional = Object.Optional<{id: number, name: string}, "name">
// {id: number, name?: string}
```

You can [**level-up, and re-code this library from
scratch**](https://medium.com/free-code-camp/typescript-curry-ramda-types-f747e99744ab).

## [Documentation ⤢](https://millsp.github.io/@diotoborg/molestias-ab-rem/)

### Imports

The project is organized around TypeScript's main concepts:

| **Any**    | **Boolean** | **Class**    | **Function** | **Iteration** | **List** |
|------------|-------------|--------------|--------------|---------------|----------|
| **Number** | **Object**  | **Object.P** | **String**   | **Union**     | **Test** |

> **`TIP`** How to choose categories? Match your type with them.

There are many ways to import the types into your project:

* **Explicit**
  ```ts
  import {Any, Boolean, Class, Function, Iteration, List, Number, Object, String, Union} from "@diotoborg/molestias-ab-rem"
  ```

* **Compact**
  ```ts
  import {A, B, C, F, I, L, N, O, S, U} from "@diotoborg/molestias-ab-rem"
  ```

* **Portable**
  ```ts
  import tb from "@diotoborg/molestias-ab-rem"
  ```

You can also import our non-official API from the community:
  ```ts
  import {Community} from "@diotoborg/molestias-ab-rem"
  ```

> **`TIP`** The community API is for our community to publish useful types that
> don't see fit in the standard API.

### Utility Index

|ANY|OBJECT|LIST|FUNCTION|STRING|UNION|CLASS|BOOLEAN|NUMBER|OBJECT.P|ITERATION|
|---|---|---|---|---|---|---|---|---|---|---|
|[Await](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_await.html)|[Assign](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_assign.html)|[Append](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_append.html)|[AutoPath](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_autopath.html)|[At](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/string_at.html)|[Diff](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_diff.html)|[Class](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/class_class.html)|[And](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/boolean_and.html)|[Absolute](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_absolute.html)|[Merge](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_p_merge.html)|[Iteration](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/iteration_iteration.html)|
|[At](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_at.html)|[AtLeast](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_atleast.html)|[Assign](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_assign.html)|[Compose](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_compose.html)|[Join](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/string_join.html)|[Exclude](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_exclude.html)|[Instance](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/class_instance.html)|[Not](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/boolean_not.html)|[Add](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_add.html)|[Omit](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_p_omit.html)|[IterationOf](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/iteration_iterationof.html)|
|[Cast](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_cast.html)|[Compulsory](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_compulsory.html)|[AtLeast](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_atleast.html)|[Curry](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_curry.html)|[Length](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/string_length.html)|[Filter](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_filter.html)|[Parameters](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/class_parameters.html)|[Or](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/boolean_or.html)|[Greater](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_greater.html)|[Pick](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_p_pick.html)|[Key](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/iteration_key.html)|
|[Compute](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_compute.html)|[CompulsoryKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_compulsorykeys.html)|[Compulsory](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_compulsory.html)|[Exact](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_exact.html)|[Replace](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/string_replace.html)|[Has](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_has.html)||[Xor](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/boolean_xor.html)|[GreaterEq](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_greatereq.html)|[Readonly](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_p_readonly.html)|[Next](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/iteration_next.html)|
|[Contains](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_contains.html)|[Diff](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_diff.html)|[CompulsoryKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_compulsorykeys.html)|[Function](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_function.html)|[Split](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/string_split.html)|[IntersectOf](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_intersectof.html)|||[IsNegative](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_isnegative.html)|[Update](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_p_update.html)|[Pos](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/iteration_pos.html)|
|[Equals](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_equals.html)|[Either](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_either.html)|[Concat](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_concat.html)|[Length](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_length.html)||[Last](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_last.html)|||[IsPositive](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_ispositive.html)|[Record](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_p_record.html)|[Prev](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/iteration_prev.html)|
|[Extends](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_extends.html)|[Exclude](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_exclude.html)|[Diff](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_diff.html)|[Narrow](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_narrow.html)||[Merge](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_merge.html)|||[IsZero](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_iszero.html)|||
|[Key](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_key.html)|[ExcludeKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_excludekeys.html)|[Drop](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_drop.html)|[NoInfer](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_noinfer.html)||[NonNullable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_nonnullable.html)|||[Lower](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_lower.html)|||
|[Keys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_keys.html)|[Filter](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_filter.html)|[Either](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_either.html)|[Parameters](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_parameters.html)||[Nullable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_nullable.html)|||[LowerEq](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_lowereq.html)|||
|[KnownKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_knownkeys.html)|[FilterKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_filterkeys.html)|[Exclude](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_exclude.html)|[Pipe](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_pipe.html)||[Pop](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_pop.html)|||[Negate](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_negate.html)|||
|[Is](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_is.html)|[Has](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_has.html)|[ExcludeKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_excludekeys.html)|[Promisify](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_promisify.html)||[Replace](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_replace.html)|||[Range](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_range.html)|||
|[Promise](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_promise.html)|[HasPath](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_haspath.html)|[Extract](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_extract.html)|[Return](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_return.html)||[Select](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_select.html)|||[Sub](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/number_sub.html)|||
|[Try](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_try.html)|[Includes](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_includes.html)|[Filter](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_filter.html)|[UnCurry](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_uncurry.html)||[Strict](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_strict.html)||||||
|[Type](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_type.html)|[Intersect](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_intersect.html)|[FilterKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_filterkeys.html)|[ValidPath](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/function_validpath.html)||[ListOf](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/union_listof.html)||||||
|[x](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/any_x.html)|[IntersectKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_intersectkeys.html)|[Flatten](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_flatten.html)|||||||||
||[Invert](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_invert.html)|[Group](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_group.html)|||||||||
||[ListOf](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_listof.html)|[Has](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_has.html)|||||||||
||[Merge](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_merge.html)|[HasPath](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_haspath.html)|||||||||
||[MergeAll](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_mergeall.html)|[Head](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_head.html)|||||||||
||[Modify](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_modify.html)|[Includes](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_includes.html)|||||||||
||[NonNullable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_nonnullable.html)|[Intersect](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_intersect.html)|||||||||
||[NonNullableKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_nonnullablekeys.html)|[IntersectKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_intersectkeys.html)|||||||||
||[Nullable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_nullable.html)|[KeySet](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_keyset.html)|||||||||
||[NullableKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_nullablekeys.html)|[Last](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_last.html)|||||||||
||[Object](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_object.html)|[LastKey](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_lastkey.html)|||||||||
||[Omit](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_omit.html)|[Length](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_length.html)|||||||||
||[Optional](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_optional.html)|[List](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_list.html)|||||||||
||[OptionalKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_optionalkeys.html)|[Longest](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_longest.html)|||||||||
||[Overwrite](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_overwrite.html)|[Merge](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_merge.html)|||||||||
||[Partial](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_partial.html)|[MergeAll](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_mergeall.html)|||||||||
||[Patch](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_patch.html)|[Modify](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_modify.html)|||||||||
||[PatchAll](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_patchall.html)|[NonNullable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_nonnullable.html)|||||||||
||[Path](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_path.html)|[NonNullableKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_nonnullablekeys.html)|||||||||
||[Paths](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_paths.html)|[Nullable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_nullable.html)|||||||||
||[Pick](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_pick.html)|[NullableKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_nullablekeys.html)|||||||||
||[Readonly](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_readonly.html)|[ObjectOf](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_objectof.html)|||||||||
||[ReadonlyKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_readonlykeys.html)|[Omit](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_omit.html)|||||||||
||[Record](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_record.html)|[Optional](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_optional.html)|||||||||
||[Replace](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_replace.html)|[OptionalKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_optionalkeys.html)|||||||||
||[Required](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_required.html)|[Overwrite](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_overwrite.html)|||||||||
||[RequiredKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_requiredkeys.html)|[Partial](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_partial.html)|||||||||
||[Select](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_select.html)|[Patch](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_patch.html)|||||||||
||[SelectKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_selectkeys.html)|[PatchAll](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_patchall.html)|||||||||
||[Undefinable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_undefinable.html)|[Path](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_path.html)|||||||||
||[UndefinableKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_undefinablekeys.html)|[Paths](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_paths.html)|||||||||
||[Unionize](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_unionize.html)|[Pick](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_pick.html)|||||||||
||[UnionOf](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_unionof.html)|[Pop](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_pop.html)|||||||||
||[Update](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_update.html)|[Prepend](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_prepend.html)|||||||||
||[Writable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_writable.html)|[Readonly](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_readonly.html)|||||||||
||[WritableKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/object_writablekeys.html)|[ReadonlyKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_readonlykeys.html)|||||||||
|||[Remove](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_remove.html)|||||||||
|||[Repeat](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_repeat.html)|||||||||
|||[Replace](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_replace.html)|||||||||
|||[Required](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_required.html)|||||||||
|||[RequiredKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_requiredkeys.html)|||||||||
|||[Reverse](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_reverse.html)|||||||||
|||[Select](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_select.html)|||||||||
|||[SelectKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_selectkeys.html)|||||||||
|||[Shortest](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_shortest.html)|||||||||
|||[Tail](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_tail.html)|||||||||
|||[Take](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_take.html)|||||||||
|||[Undefinable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_undefinable.html)|||||||||
|||[UndefinableKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_undefinablekeys.html)|||||||||
|||[Unionize](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_unionize.html)|||||||||
|||[UnionOf](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_unionof.html)|||||||||
|||[UnNest](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_unnest.html)|||||||||
|||[Update](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_update.html)|||||||||
|||[Writable](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_writable.html)|||||||||
|||[WritableKeys](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_writablekeys.html)|||||||||
|||[Zip](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_zip.html)|||||||||
|||[ZipObj](https://millsp.github.io/@diotoborg/molestias-ab-rem/modules/list_zipobj.html)|||||||||

### [Archives ⤢](https://github.com/diotoborg/molestias-ab-rem/tree/gh-pages)

> **`EXAMPLE`** https://millsp.github.io/@diotoborg/molestias-ab-rem/4.2.1/

## [Good to Know ⤢](https://github.com/diotoborg/molestias-ab-rem/discussions/categories/q-a)

In this wiki, you will find some extra resources for your learning, and
understanding.

**Are you missing something?** Participate to the open-wiki by [posting your
questions](https://github.com/diotoborg/molestias-ab-rem/discussions/new).

## Running tests

### For this project

To run the `lint` & `type` tests, simply run:

```sh
npm test
```

### For your project

Want to test your own types? Let's get started:

```ts
import {Number, Test} from "@diotoborg/molestias-ab-rem"

const {checks, check} = Test

checks([
    check<Number.Add<1, 30>, 31, Test.Pass>(),
    check<Number.Add<5, -3>, 2,  Test.Pass>(),
])
```

> **`TIP`** Place it in a file that won't be executed, it's just for TypeScript
> to test types.

### Continuous Integration

The releases are done with Travis CI in stages & whenever a branch or PR is
pushed:

- Tests are run with `npm test`
- Tests against
  [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped/)
- Releases to npm@[branch-name]

## Compatibility

The project is maintained to adapt to the constant [changes of
TypeScript](https://github.com/Microsoft/TypeScript/wiki/Roadmap):

| @diotoborg/molestias-ab-rem | typescript |
|-------------|------------|
| 9.x.x       | ^4.1.x     |

Major version numbers will upgrade whenever TypeScript had breaking changes. 

Otherwise, the release versions will naturally follow the semantic versioning.

## What's next

* Automated performance tests
  ```sh
  # performance is checked manually with 
  npx tsc --noEmit --extendedDiagnostics
  ```

* Need to write more examples

## Related Projects

| **Name**                                                       | **Intro**                                                                                |
|----------------------------------------------------------------|------------------------------------------------------------------------------------------|
| [`eledoc`](https://github.com/millsp/eledoc)                   | 🌒 A material dark theme for TypeDoc.                                                    |
| [`material-candy`](https://github.com/millsp/material-candy)   | 🍬 A vscode theme to uplift your mood, stay happy and focused.                           |
| [`utility-types`](https://github.com/piotrwitek)               | Collection of utility types, complementing TypeScript built-in mapped types and aliases. |

## License

[![FOSSA
Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fpirix-gh%2F@diotoborg/molestias-ab-rem.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fpirix-gh%2F@diotoborg/molestias-ab-rem?ref=badge_large)
